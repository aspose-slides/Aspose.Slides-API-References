---
title: WriteAllLines()
second_title: Aspose.Slides for C++ API 參考
description: 建立新文字檔或覆寫現有的檔案，並將指定的可列舉字串集合中的所有字串寫入該檔案，每個字串佔一行，使用指定的編碼。
type: docs
weight: 456
url: /zh-hant/system.io/file/writealllines/
---
## File::WriteAllLines(const String&, const SharedPtr<Collections::Generic::IEnumerable<String>>, const EncodingPtr&) 方法

建立新文字檔或覆寫已存在的檔案，並將指定的可列舉字串集合中的所有字串寫入檔案，每個字串占一行，使用指定的編碼。

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | 要建立或覆寫的檔案 |
| contents | const [SharedPtr](../../../system/sharedptr/)<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)<[String](../../../system/string/)>>& | 可列舉的字串集合 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | 要使用的字元編碼 |

## File::WriteAllLines(const String&, const ArrayPtr<String>&, const EncodingPtr&) 方法

建立新文字檔或覆寫已存在的檔案，並將指定的字串陣列中的所有字串寫入檔案，每個字串占一行，使用指定的編碼。

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | 要建立或覆寫的檔案 |
| contents | const [ArrayPtr](../../../system/arrayptr/)<[String](../../../system/string/)>& | 字串陣列 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | 要使用的字元編碼 |

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [EncodingPtr](../../../system/encodingptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)