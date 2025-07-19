Resonark_Music_Edit_Core.exe
Resonarkの曲の追加や削除するexeファイル

Resonark_Music_Select_Core.exe
Resonarkの曲を3曲まで選曲するexeファイル

Resonark_Music_Calculator_Core.exe
Resonarkの曲のレートを3曲まで計算するexeファイル

Music_List.csv
曲リスト

Music_List.csv.backup
Music_Listのバックアップ。バックアップから復元する際は「.backup」の部分を取り除くこと。
また、バックアップはResonark_Music_Edit_Core.exeで可能。

Music_Result_List.csv
曲のスコアとTechRate、Rateを格納したcsvファイル

Music_Result_List.csv.backup
Music_Result_Listのバックアップ。バックアップから復元する際は「.backup」の部分を取り除くこと。
また、バックアップはResonark_Music_Edit_Core.exeで可能。

v1.1.0
曲固定機能の追加

v1.2.0
Distance/GripまたはTrigger交換機能を追加
レートの範囲を指定する機能を追加

例えば、難易度7のみで行いたい場合はレートの範囲を0.49に指定し
レートを7.49に指定することで7.0～7.98までとなり
RRSVレート7.0～7.9までを選択することが可能になる。
(レート範囲0.5でレートを7.5に指定すると8.0まで巻き込まれる)

v2.0.0
難易度を追加
Easy(レート)、Normal(レート)、Hard(レート)の3つの難易度を搭載
曲難易度で考慮も可能(以前まではこれ)

計算機を追加
最大3つまでの平均レートを計算可能
また、自分自身のレートが全体の何%かの表記も搭載

v2.1.0
Music_Result_List.csvを追加
自己ベストとの比較機能搭載