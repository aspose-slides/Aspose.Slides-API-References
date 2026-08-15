---
title: get_IsWriteProtected()
second_title: Aspose.Slides for C++ API 參考
description: 取得一個值，指示綁定的簡報是否受到寫入保護。
type: docs
weight: 27
url: /zh-hant/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() 方法


取得一個值，指示綁定的簡報是否受到寫入保護。

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## 備註



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


如果簡報受密碼保護以供開啟，則屬性值等於 NotDefined. 
## 另請參閱

* 列舉 [NullableBool](../../nullablebool/)
* 類別 [PresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)