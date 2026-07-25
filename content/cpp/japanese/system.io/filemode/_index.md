---
title: FileMode
second_title: Aspose.Slides for C++ API リファレンス
description: ファイルをどのように開くかを指定します。
type: docs
weight: 508
url: /ja/system.io/filemode/
---
## FileMode 列挙体

ファイルを開く方法を指定します。

```cpp
enum class FileMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| CreateNew | 1 | 新しいファイルを作成します。ファイルがすでに存在する場合、例外がスローされます。 |
| Create | 2 | 新しいファイルを作成します。ファイルがすでに存在する場合、上書きされます。 |
| Open | 3 | 既存のファイルを開きます。ファイルが存在しない場合、例外がスローされます。 |
| OpenOrCreate | 4 | 既存のファイルを開くか、存在しない場合は新しく作成します。 |
| Truncate | 5 | 既存のファイルを開き、内容を空に切り詰めます。ファイルが存在しない場合、例外がスローされます。 |
| Append | 6 | 既存のファイルを開いて末尾にシークするか、存在しない場合は新しく作成します。 |

## 参照

* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)