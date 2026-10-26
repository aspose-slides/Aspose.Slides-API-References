---
title: get_IsPasswordProtected()
second_title: Aspose.Slides C++ API 參考文件
description: 取得一個值，指示已綁定的簡報是否受密碼保護以開啟。
type: docs
weight: 14
url: /zh-hant/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() 方法


取得一個值，指示已綁定的簡報是否受密碼保護以開啟。

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## 備註



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## 另請參閱

* 類別 [PresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)