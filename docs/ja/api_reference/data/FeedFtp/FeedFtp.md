# FeedFtp
FeedFtpオブジェクトは、FTP設定情報を保持します。

### Service
+ [FeedFtpService](../../services/FeedFtpService.md)

### Namespace
[FeedFtpService#Namespace](../../services/FeedFtpService.md#namespace)

| Field | Type | Description | response | add | set 
|---|---|---|---|---|---|
| accountId| xsd:long| アカウントID | ○ | Ignore |　Ignore 
| feedHolderId| xsd:long| FeedHolderを識別するId | ○ | Requirement | Requirement 
| itemListUploadType| [ItemListUploadType](./ItemListUploadType.md)| アップロードタイプ |  ○ | Requirement | Optional 
| schedule| Schedule <br> inherited [ScheduleHourly](./ScheduleHourly.md) <br> inherited [ScheduleDaily](./ScheduleDaily.md) <br> inherited [ScheduleWeekly](./ScheduleWeekly.md) | スケジュール | ○ | Requirement | Optional 
| feedUrl| xsd:string| FTPのURL | ○ | Requirement | Optional 
| userName| xsd:string| FTPユーザー名 | ○ | Requirement | Optional 
| userPassword| xsd:string| FTPパスワード | ○ | Requirement | Optional 
| activeStatus| [ActiveStatus](./ActiveStatus.md)| 有効フラグ <br> ※Default値：ACTIVE| ○ | Optional | Optional 

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>
