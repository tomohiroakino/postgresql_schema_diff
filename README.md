## 実行方法

```
$ ./create_schema_diff
```

## 出力ファイル
以下の4ファイルがschemaフォルダに出力される

116のdump: dump_116_YmdHMS.sql
56のdump: dump_56_YmdHMS.sql
56を116と同じにするためのステートメント: update_56_diff_YmdHMS.sql
116を56と同じにするためのステートメント: update_116_diff_YmdHMS.sql
