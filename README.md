# House Prices: Advanced Regression Techniques
kaggleのコンペに参加：789位（Top46%）<br>
分析アプローチ：<br>

1.特徴量の設計<br>
	＜特徴量作成＞<br>
		①割り算<br>
		②フロア合計平米数<br>
		③評価建築年(改修と品質を考慮) <br>
		④エリアごと平均と比較した相対値（リビングや敷地面積など）<br>
	＜特徴量選択＞<br>
		・重要度(feature_importance)が低いものを削除<br>
		・変数増加法<br>

2.アルゴリズムの選択　※ sklearnでできるもの<br>
	①ランダムフォレスト<br>
	②ニューラルネットワーク<br>
	③AdaBoost<br>
	④GradientBoos<br>
