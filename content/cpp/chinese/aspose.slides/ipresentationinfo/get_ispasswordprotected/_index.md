---
title: get_IsPasswordProtected()
second_title: Aspose.Slides C++ API 参考
description: 获取一个值，用于指示绑定的演示文稿是否被密码保护以打开。
type: docs
weight: 14
url: /zh/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() 方法

获取一个值，指示绑定的演示文稿是否被密码保护以打开。

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## 备注


```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## 另请参见

* 类 [IPresentationInfo](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)