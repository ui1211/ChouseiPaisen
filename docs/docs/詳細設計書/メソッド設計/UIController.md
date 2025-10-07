## 概要
調整パイセンのUIのウィジェットの機能
Service層へ依存して、処理結果を受け取ってUI更新を担う

## メソッド一覧

| ID   | メソッド名              | イベント  | 機能概要                              |
| ---- | ----------------------- | --------- | ------------------------------------- |
| 2-1  | popup_menu_sheet        | on_click  | ポップアップウィンドウを表示          |
| 2-2  | textbox_sheet_url       | on_change | URLからスプレッドシートIDを抽出       |
| 2-3  | dropbox_sheet_name      | on_click  | 日程調整シート名を指定                |
| 2-4  | button_reflect          | on_click  | 日程調整シートメタデータを保存        |
| 2-5  | textbox_chousei_url     | on_key    | 調整さんURL入力→Enter後スクレイピング |
| 2-6  | table_booking_check     | on_load   | ブッキングチェック結果を表示          |
| 2-7  | label_title             | on_click  | 調整さんイベント名をリンク表示        |
| 2-8  | button_add_schdule_data | on_click  | 調整さんデータ保存し予定一覧に追加    |
| 2-9  | table_schdule           | on_load   | 予定一覧を表示                        |
| 2-10 | label_title             | on_click  | 予定イベント名/会議名をリンク表示     |
| 2-11 | dropdown_user_name      | on_click  | ユーザー名リスト生成・更新            |
| 2-12 | label_update_time       | on_load   | 最終更新時間を表示                    |
| 2-13 | button_delete           | on_click  | 予定一覧データの削除フラグを設定      |
| 2-14 | button_all_update       | on_click  | 予定データを全件更新                  |
| 2-15 | table_reservation       | on_load   | 予約一覧を表示                        |
| 2-16 | button_sort_by_time     | on_click  | 予約一覧を時間で昇順/降順切替         |