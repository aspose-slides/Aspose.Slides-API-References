---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API 参考
description: 获取一个值，指示绑定的演示文稿是否受到打开密码的保护。
type: docs
weight: 14
url: /zh/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() 方法


获取一个值，指示绑定的演示文稿是否受到打开密码的保护。

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## 备注



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## 另请参阅

* 类 [PresentationInfo](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)