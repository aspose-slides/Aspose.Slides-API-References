---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すファイルを指定された場所へコピーします。コピー先のファイルがすでに存在する場合、コピーは失敗します。
type: docs
weight: 105
url: /ja/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) メソッド

現在のオブジェクトが表すファイルを指定された場所へコピーします。コピー先のファイルがすでに存在する場合、コピーは失敗します。

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | コピー先のファイル名 |

### 戻り値

コピーを表す [FileInfo](../) オブジェクト

## FileInfo::CopyTo(const String\&, bool) メソッド

現在のオブジェクトが表すファイルを指定された場所へコピーします。パラメータは、既存のコピー先ファイルを上書きするかどうかを指定します。

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | コピー先のファイル名 |
| overwrite | **bool** | コピー先ファイルが既に存在する場合に上書きする場合は true、上書きせずに失敗させる場合は false |

### 戻り値

コピーを表す [FileInfo](../) オブジェクト

## 参照

* 型定義 [FileInfoPtr](../../../system/fileinfoptr/)
* クラス [String](../../../system/string/)
* クラス [FileInfo](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)