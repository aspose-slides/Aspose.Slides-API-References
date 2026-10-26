---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたバッファサイズとオプションを使用して、新しいファイルを作成（または既存のファイルを上書き）し、読み取りおよび書き込みアクセス用に開きます。
type: docs
weight: 53
url: /ja/system.io/file/create/
---
## File::Create(const String&, int32_t, FileOptions) メソッド

新しいファイルを作成（または既存ファイルを上書き）し、指定されたバッファサイズとオプションを使用して読み取りおよび書き込みアクセス用に開きます。

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 作成または上書きするファイルのパス |
| bufferSize | **int32_t** | ファイルの読み取りおよび書き込み時にバッファリングされるバイト数 |
| options | [FileOptions](../../fileoptions/) | ファイルを作成または上書きする方法を指定します |

### 戻り値

指定されたファイルに関連付けられた [FileStream](../../filestream/) オブジェクトへの 共有ポインタ

## 関連項目

* 列挙型 [FileOptions](../../fileoptions/)
* 型定義 [FileStreamPtr](../../../system/filestreamptr/)
* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)