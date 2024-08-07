# google-calendar-notification

## LINE Notify

[LINE Notify](https://notify-bot.line.me/ja/) のマイページから家族グループのトークンを発行する。

## Google Cloud

Google Calendar API を有効にして IAM と管理からサービスアカウントを発行して自分の Google Calender の設定のマイカレンダーにサービスアカウントのメールアドレスを「特定のユーザーまたはグループと共有する」に追加してアクセスを許可させる。

## AWS 

EventBridge Scheduler --> Lambda で毎日20時に今週と来週の予定を LINE に通知する。
