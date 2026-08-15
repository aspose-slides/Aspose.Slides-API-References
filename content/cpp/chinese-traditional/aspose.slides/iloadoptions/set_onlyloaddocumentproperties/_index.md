---
title: set_OnlyLoadDocumentProperties()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性僅在簡報檔案受密碼保護時有意義。值為 true 表示只能從加密的簡報檔案載入文件屬性，且忽略密碼。值為 false 表示必須使用正確的密碼載入整個加密的簡報。若簡報未加密，則屬性值始終會被忽略。若加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，並會拋出例外。寫入 bool.
type: docs
weight: 144
url: /zh-hant/aspose.slides/iloadoptions/set_onlyloaddocumentproperties/
---
## ILoadOptions::set_OnlyLoadDocumentProperties(bool) 方法

此屬性僅在簡報檔案受密碼保護時有意義。值為 true 時表示只需從加密的簡報檔案載入文件屬性，且忽略密碼。值為 false 時表示必須使用正確的密碼載入整個加密的簡報。若簡報未加密，則屬性值始終會被忽略。若加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，並會拋出例外。寫入 **bool**。

```cpp
virtual void Aspose::Slides::ILoadOptions::set_OnlyLoadDocumentProperties(bool value)=0
```

## 另見

* 類別 [ILoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)