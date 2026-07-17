---
title: get_IsWriteProtected()
second_title: Aspose.Slides C++ API 参考
description: 获取一个值，用于指示绑定的演示文稿是否受写保护。
type: docs
weight: 27
url: /zh/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() 方法


获取一个值, 用于指示绑定的演示文稿是否受写保护。

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## 备注



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


如果演示文稿受打开密码保护，则属性值等于 NotDefined。参见 [NullableBool](../../nullablebool/) 枚举。 
## 另请参见

* 枚举 [NullableBool](../../nullablebool/)
* 类 [IPresentationInfo](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)