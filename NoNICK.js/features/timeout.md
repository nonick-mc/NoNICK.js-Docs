---
icon: dot
tag: [スラッシュコマンド]
author: 
- name: NoNICK
  avatar: https://media.discordapp.net/attachments/958791423161954445/975266759529623652/-3.png?width=663&height=663
order: 75
---
# /timeout
!!!success
このコマンドの実行には `メンバーをタイムアウト` 権限が必要です。
!!!

メンバーを指定した時間分 (最大28日) タイムアウトします。1分単位での指定が可能で、**公式のビルトインコマンドよりも柔軟なタイムアウトが可能です。**

![](../static/features/timeout_1.png)

## コマンド引数
引数                                              | 説明
---                                               | ---
`user` [!badge variant="danger" text="必須"]   | タイムアウトするメンバー (IDのみでも可能)
`day` [!badge variant="danger" text="必須"]    | タイムアウトする日数
`hour` [!badge variant="danger" text="必須"]   | タイムアウトする時数
`minute` [!badge variant="danger" text="必須"] | タイムアウトする分数
`reason`                                       | 理由

!!! warning 以下の条件を満たすとエラーが発生します。
* `day` `hour` `minute`の合計が28日を超えるタイムアウト
* コマンド実行者よりロールが上のメンバーをタイムアウト
* BOTよりロールが上のメンバーをタイムアウト
!!!

!!!
コマンド実行後は、理由と実行者のユーザーネームが監査ログに記入されます。
!!!
