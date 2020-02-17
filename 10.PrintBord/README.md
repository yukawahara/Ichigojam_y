# フォルダ説明
* 0.Library
** パーツライブラリー、自作パーツ等を保存する

* 1.Tools
** Eagleで利用ツールを保存

* 2.Project
** Eagle でプロジェクトを作成した時に保存するもの
【プロジェクト命名規則】
プロジェクト名は下記とすること
```
年２桁_P連番_基盤名

例)
20_P01_EEPROM
```

【ボード命名規則】
プロジェクト名は下記とすること
```
B連番_基盤名_バージョン_備考

例)
B01_EEPROM_v1.0_〇〇
```

* 3.Order_Duplication
** 発注前に複製したデータを保存する。
** 保存する時は、「フォルダー」と「説明テキスト」を記載すること
【フォルダの命名規則】
```
年２桁_D連番_Pから始まるベースとなった基盤の番号-そのバージョン

例)
20_D01_P001-v1.0+P002-v1.0

```


* 10.Order
** 発注時に作成したデータを保存する。
** ここに保存するのは、ZIPファイルのみ
** 発注時に変更した時は