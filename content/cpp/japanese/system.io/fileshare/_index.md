---
title: FileShare
second_title: Aspose.Slides for C++ API リファレンス
description: 開かれているファイルに対して、他の FileStream オブジェクトが持つことができるアクセスの種類を指定します。
type: docs
weight: 534
url: /ja/system.io/fileshare/
---
## FileShare 列挙型

開かれているファイルに対して、他の [FileStream](../filestream/) オブジェクトが持つことができるアクセスの種類を指定します。

```cpp
enum class FileShare
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | アクセスなし。 |
| Read | 1 | 読み取り専用アクセス。 |
| Write | 2 | 書き込み専用アクセス。 |
| ReadWrite | 3 | 読み取りおよび書き込みアクセス。 |
| Delete | 4 | ファイルを削除できます。 |
| Inheritable | 16 | 子プロセスがファイルハンドルを継承できるようにします。 |

## 参照

* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)