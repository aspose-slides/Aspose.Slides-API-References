---
title: get_Password()
second_title: Aspose.Slides for C++ API 参考
description: "获取密码。读取 System::String."
type: docs
weight: 105
url: /zh/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() 方法

获取密码。读取 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## 备注

密码。

下面的示例代码展示了如何打开受密码保护的 PowerPoint [Presentation](../../presentation/)。 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// 使用已解密的演示文稿
```

## 另见

* 类 [String](../../../system/string/)
* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)