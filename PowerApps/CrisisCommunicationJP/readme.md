# 社内緊急対策ソリューション
*社内緊急対策* アプリは、緊急対策に関する情報を提供し、素早く社内報やよくある質問などの確認、
緊急連絡先などの重要な情報にアクセスできます。
このアプリを利用するには最小限のセットアップで利用可能です。

ブログ投稿については [こちらで公式のもの](https://powerapps.microsoft.com/en-us/blog/crisis-communication-a-power-platform-template/)がご覧いただけます。
日本語でのブログ投稿については [こちらで](https://memo.tyoshida.me/power-platform/powerapps/crisis-communication-template-released)ご覧いただけます。

日本語訳の [ブログ投稿](https://memo.tyoshida.me/power-platform/powerapps/crisis-communication-template-released)では、以下のセットアップについてご確認いただけます:
- データ保管場所の作成
- 社内緊急対策アプリと管理用アプリのインポート方法
- アプリ用コンテンツの作成方法
- ユーザーへの通知用フローのセットアップ方法
- 情報の収集と問題解決にあたっての集中対策本部を設立するためのTeamsチームの作成方法

## ダウンロード
[こちらから](https://github.com/taiki-yoshida/powerplatform/raw/master/PowerApps/CrisisCommunicationJP/CrisisCommunicationJP.zip)入手いただけます。
ZIPファイルを展開後、中に含まれるZIPファイルは、解凍しないでください。

## 更新情報
日付（日本時間） | 備考
-|-
2020.03.05 | 英語版初版リリース: <br>1. "CrisisCommunication.zip" - Canvas App for end users<br>2. "CrisisCommunicationAdmin.zip" - Canvas App for administrating the content <br>3. "DeploySPLists.zip" - Flow to initialize SharePoint Online Lists for managing content <br>4. "CrisisCommunicationNewsNotification.zip" - Flow to send out notifications when company news updates are published <br>5. "Presence status report.pbix" - Power BI Dashboard to monitor absences and other data
2020.03.06 | 日本語版初版リリース: <br>1. "社内緊急対策アプリ.zip" - エンドユーザー向けのキャンバスアプリ<br>2. "社内緊急対策（管理者用）アプリ.zip" - 管理者用のキャンバスアプリ <br>3. "SharePointリスト作成フロー.zip" - SharePoint Online のカスタムリストを作成するためのPower Automateフロー <br>4. "新しい社内報の投稿を通知.zip" - 社内報が新規で投稿された場合の通知用のPower Automateフロー <br>5. "状況確認レポート.pbix" - 在宅勤務者情報など、そのほかデータの状況確認のためのPower BI ダッシュボード

## サポートへのお問い合わせ
本ソリューションを利用するにあたって、マイクロソフトコーポレーション並びに日本マイクロソフト株式会社へサポートチケットは発行いただけません。ソリューションに関するお問い合わせにつきましては、[こちらへ](https://github.com/microsoft/powerapps-tools/issues/new?assignees=denisem-msft&labels=crisiscommapp&template=-crisis-communication-app--bug-report.md&title=%5BBUG%5D%3A+issue+title)ご投稿ください。ベストエフォートでの対応となりますことを予めご了承ください。

### 免責事項
*本ソリューションはサンプルとして提供されており、Microsoft Power AppsやMicrosoft Teamsへ試行いただくためのものです。本ソリューションは医療現場、医療機器、緊急機関への連絡手段などへの利用として意図されておらず、マイクロソフトコーポレーション並びに日本マイクロソフト株式会社（以下、マイクロソフト）によってそれらに関連する用途のための許可・許諾は得ておりません。本ソリューションを通じた専門的見解や診断、治療、判断を得るための代替手段として利用しないでください。本ソリューションをご利用される場合、利用にあたる責任やリスクは利用者にあるものとし、マイクロソフトは一切の責任を取らないものとします。*