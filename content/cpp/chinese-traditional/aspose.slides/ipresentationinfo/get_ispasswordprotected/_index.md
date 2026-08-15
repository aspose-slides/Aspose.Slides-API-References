---
title: get_IsPasswordProtected()
second_title: Aspose.Slides C++ API 參考
description: 取得一個值，用於指示已綁定的簡報是否受密碼保護以開啟。
type: docs
weight: 14
url: /zh-hant/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() 方法


取得一個值，指示綁定的簡報是否受到開啟密碼的保護。

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## 備註



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## 另請參閱

* 類別 [IPresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)