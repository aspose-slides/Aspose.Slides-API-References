---
title: Open()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたモードで読み取りおよび書き込みを行い、共有なしで指定されたファイルを開きます。
type: docs
weight: 235
url: /ja/system.io/file/open/
---
## File::Open(const String\&, FileMode) メソッド


指定されたファイルを、指定されたモードで読み取りおよび書き込み用に、共有なしで開きます。

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 開くファイルのパス |
| mode | [FileMode](../../filemode/) | ファイルを開くモードを指定します |

### 戻り値

開かれたファイルに関連付けられた [FileStream](../../filestream/) オブジェクト

## File::Open(const String\&, FileMode, FileAccess, FileShare) メソッド


指定されたファイルを、指定されたモードで、指定されたアクセス種別と共有オプションを使用して開きます。

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 開くファイルのパス |
| mode | [FileMode](../../filemode/) | ファイルを開くモードを指定します |
| access | [FileAccess](../../fileaccess/) | 要求されたアクセス種別 |
| share | [FileShare](../../fileshare/) | 他の [FileStream](../../filestream/) オブジェクトが開かれたファイルに対して持つアクセス種別 |

### 戻り値

開かれたファイルに関連付けられた [FileStream](../../filestream/) オブジェクト

## 参照

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)