---
title: FileStream()
second_title: Aspose.Slides for C++ API リファレンス
description: FileStream クラスの新しいインスタンスを作成し、指定されたパラメータで初期化します。
type: docs
weight: 1
url: /ja/system.io/filestream/filestream/
---
## FileStream::FileStream(const String&, FileMode) コンストラクタ


指定されたパラメータで [FileStream](../) クラスの新しいインスタンスを作成し、初期化します。

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | 開くファイルのパス。 |
| mode | [FileMode](../../filemode/) | ファイルを開くモードを指定します。 |

## FileStream::FileStream(const String&, FileMode, FileAccess, FileShare, int32_t, FileOptions) コンストラクタ


指定されたパラメータで [FileStream](../) クラスの新しいインスタンスを作成し、初期化します。

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | 開くファイルのパス。 |
| mode | [FileMode](../../filemode/) | ファイルを開くモードを指定します。 |
| access | [FileAccess](../../fileaccess/) | 要求されたアクセス種別。 |
| share | [FileShare](../../fileshare/) | 他の [FileStream](../) オブジェクトが開かれたファイルに対して持つアクセス種別。 |
| buffer_size | **int32_t** | 読み取りおよび書き込み操作中にバッファされるバイト数。 |
| options | [FileOptions](../../fileoptions/) | 追加オプション。 |

## FileStream::FileStream(const String&, FileMode, FileAccess, FileShare, int32_t, bool) コンストラクタ


指定されたパラメータで [FileStream](../) クラスの新しいインスタンスを作成し、初期化します。

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | 開くファイルのパス。 |
| mode | [FileMode](../../filemode/) | ファイルを開くモードを指定します。 |
| access | [FileAccess](../../fileaccess/) | 要求されたアクセス種別。 |
| share | [FileShare](../../fileshare/) | 他の [FileStream](../) オブジェクトが開かれたファイルに対して持つアクセス種別。 |
| buffer_size | **int32_t** | 読み取りおよび書き込み操作中にバッファされるバイト数。 |
| useAsync | **bool** | 非同期 I/O を使用するか、同期 I/O を使用するかを指定します。 |

## 備考



基礎となるオペレーティングシステムが非同期 I/O をサポートしていない可能性があります。 

## FileStream::FileStream(const FileStream&) コンストラクタ




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## 関連項目

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* クラス [String](../../../system/string/)
* クラス [FileStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)