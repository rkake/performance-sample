# performance-sample
パフォーマンス調査用サンプル

パフォーマンス調査ガイド内で使用しているサンプルです。

https://www.intersystems.com/wp-content/uploads/sites/6/InterSystems_PerformanceGuide1_2014.1_V1.0.pdf

このサンプルに含まれるファイルについてご説明します。

このサンプルはCache／Ensemble2014.1 以降、InterSystems IRIS（for Healthも含）での動作確認を行っております。
管理ポータルのDeepSeeメニューについては、2014.1以降のバージョンでの確認を推奨しています。
予めご了承ください。


(1)　HistoryCubeAll.xml

	パフォーマンス調査ガイド　～知っておこう　システムの基準値～　の説明に利用している
	ダッシュボードで履歴モニタの収集値を確認する環境作成の流れで使用しています。

	インポート手順について詳細は、ガイドのP44以降をご参照ください。


(2)　IRIS-HistoryMonitor.Installer.xml

	InterSystems IRIS／IRIS for Health用の、履歴モニタで収集した情報を Analytics（DeepSee）メニューで分析の流れ使用しています。


(3)　HistoryMonitor.Installer.xml

	Cache／Ensemble2014.1 ～2018.1でご利用いただけます。（IRIS／IRIS for Healthの場合は (2)をご利用ください）
	DeepSeeダッシュボードで履歴モニタの収集値を確認する環境インストール用に利用しています。

	（1）と同様に、使用方法詳細については、ガイドのP43以降をご参照ください。



===  (3)(4)は、ユーザ定義のタスクタイプのサンプルです


タスクの利用については、ガイド　P29以降　のタスク登録方法についての簡易説明をご参照ください。
（詳細はドキュメントもご活用ください。）

(3)　ZTask.HistoryMonitorDailyDataPurge.xml

	ガイドでは、説明だけの登場ですが　日次データ削除用　サンプルタスクです。
	(1)(2)　のインストールに使用する環境にインポートしてご利用ください。


(4)　ZTask.mgstat.xml

	ガイドに登場する ^mgstatルーチンによるシステム使用状況のデータ収集ルーチン用タスクです。
	%SYSネームスペースにインポートしてご利用ください。

以上です。
