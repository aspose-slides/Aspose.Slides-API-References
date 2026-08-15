---
title: set_OnlyLoadDocumentProperties()
second_title: Aspose.Slides for C++ API 參考文件
description: 此屬性在簡報檔案受密碼保護時才有意義。值為 true 表示只能從加密的簡報檔載入文件屬性，且密碼會被忽略。值為 false 表示必須使用正確的密碼載入整個加密的簡報。若簡報未加密，則屬性值始終會被忽略。若加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，並會拋出例外。Write bool.
type: docs
weight: 144
url: /zh-hant/aspose.slides/loadoptions/set_onlyloaddocumentproperties/
---
## LoadOptions::set_OnlyLoadDocumentProperties(bool) 方法

如果簡報檔案受密碼保護，此屬性才有意義。Value of true 表示只能從加密的簡報檔載入文件屬性，且密碼會被忽略。Value of false 表示必須使用正確的密碼載入整個加密的簡報。若簡報未加密，則屬性值總是會被忽略。若加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，並會拋出例外。Write **bool**.

```cpp
void Aspose::Slides::LoadOptions::set_OnlyLoadDocumentProperties(bool value) override
```

## 參見

* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)