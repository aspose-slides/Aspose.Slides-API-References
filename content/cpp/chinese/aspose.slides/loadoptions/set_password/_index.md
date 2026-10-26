---
title: set_Password()
second_title: Aspose.Slides for C++ API 参考
description: "设置密码。写入 System::String."
type: docs
weight: 118
url: /zh/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) 方法

设置密码。写入 [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## 备注

密码。

下面的示例代码展示了如何打开受密码保护的 PowerPoint [Presentation](../../presentation/)。 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// 处理已解密的演示文稿
```

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)