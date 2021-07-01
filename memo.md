## トラブル

* シミュレータが白い画面

**状況**

<img src="https://github.com/ryoya-cre8tor/TIL_day2/blob/main/%E3%83%86%E3%82%99%E3%83%8F%E3%82%99%E3%83%83%E3%82%AF%E3%82%99%E5%A4%B1%E6%95%97%E3%82%B3%E3%83%BC%E3%83%88%E3%82%99%202021-07-01%2017.19.02.png" width="300px"/>

このコードでデバッグすると

<img src="https://github.com/ryoya-cre8tor/TIL_day2/blob/main/%E3%83%86%E3%82%99%E3%83%8F%E3%82%99%E3%83%83%E3%82%AF%E3%82%99%E5%A4%B1%E6%95%97%E7%94%BB%E9%9D%A22021-07-01%2017.19.42.png" width="100px"/>

**解決策**
* デバッグの理解不足

[RunとDebugの違い](https://www.youtube.com/watch?v=ZvCqkvNOOew)

<img src="https://github.com/ryoya-cre8tor/TIL_day2/blob/main/%E3%83%86%E3%82%99%E3%83%8F%E3%82%99%E3%83%83%E3%82%AF%E3%82%99%E6%88%90%E5%8A%9F%E3%82%B3%E3%83%BC%E3%83%88%E3%82%99%202021-07-01%2017.20.15.png" width="300px"/>

コードに振られた番号にある赤い丸(ブレイクポイント)でプログラムを止めることができる。  
つまりデバッグは赤い丸までプログラムを動かして中身を確認する機能。  
ブレイクポイントを無視して最後まで実行したい時はRunモード。

ということで、赤い丸をクリックして消すことで

<img src="https://github.com/ryoya-cre8tor/TIL_day2/blob/main/%E3%83%86%E3%82%99%E3%83%8F%E3%82%99%E3%83%83%E3%82%AF%E3%82%99%E6%88%90%E5%8A%9F%E7%94%BB%E9%9D%A22021-07-01%2017.21.19.png" width="100px"/>

しっかりデバッグできました。
