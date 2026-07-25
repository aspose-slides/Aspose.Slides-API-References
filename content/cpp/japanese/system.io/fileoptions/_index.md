---
title: FileOptions
second_title: Aspose.Slides for C++ API リファレンス
description: FileStream オブジェクトを作成するための高度なオプションを表します。
type: docs
weight: 521
url: /ja/system.io/fileoptions/
---
## FileOptions 列挙型

[FileStream](../filestream/) オブジェクトを作成するための高度なオプションを表します。

```cpp
enum class FileOptions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | 追加オプションはありません。 |
| Encrypted | 16384 | ファイルは暗号化されています。実装されていません。 |
| DeleteOnClose | 67108864 | ファイルは使用されなくなった時に自動的に削除されるべきです。 |
| SequentialScan | 134217728 | ファイルはシーケンシャルにアクセスされるべきです。 |
| RandomAccess | 268435456 | ファイルはランダムにアクセスされます。 |
| Asynchronous | 1073741824 | ファイルは非同期 I/O 操作に使用できます。 |
| WriteThrough | n/a | すべての書き込みは中間キャッシュをバイパスして直接ディスクに行われるべきです。 |

## 参照

* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)