---
layout: lesson
root: .
---

1920年代後半から1930年代初頭にかけて、
William Dyer、Frank Pabodie、Valentina Roerichが
南太平洋の[アクセス不可能な極](https://en.wikipedia.org/wiki/Pole_of_inaccessibility)に、
続いて南極に探検を行った。 2年前、彼らの探検はMiskatonic大学のストレージロッカーで発見されました。
 私たちは、その中に含まれているデータをスキャンしてOCRしています。
ここでは、検索と分析を容易にする方法でその情報を保存したいと考えています。

ストレージのための3つの一般的なオプションは、テキストファイル、スプレッドシート、およびデータベースです。
 テキストファイルは作成が簡単でバージョン管理もうまく機能しますが、検索ツールと分析ツールを自分で構築する必要があります。 
スプレッドシートは単純な分析には適していますが、大規模または複雑なデータセットはうまく処理できません。
 ただし、データベースには検索と分析のための強力なツールが含まれており、大規模で複雑なデータセットを処理できます。 
これらのレッスンでは、データベースを使用して遠征のデータを探索する方法を示します。

> ## Prerequisites
>
> * This lesson requires the Unix shell, plus [SQLite3](http://www.sqlite.org/) or [DB Browser for SQLite](http://sqlitebrowser.org/).
> * Please download the database we will use: [survey.db]({{ page.root }}/files/survey.db)
{: .prereq}

