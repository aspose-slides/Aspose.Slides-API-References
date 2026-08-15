---
title: get_IsWriteProtected()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得一個值，用來表示已綁定的簡報是否受到寫入保護。
type: docs
weight: 27
url: /zh-hant/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() method


取得一個值，用來表示綁定的簡報是否受到寫入保護。

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## 備註



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


如果簡報受到開啟密碼的保護，屬性值等於 NotDefined。請參閱 [NullableBool](../../nullablebool/) 列舉。 
## 參見

* 列舉 [NullableBool](../../nullablebool/)
* 類別 [IPresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)