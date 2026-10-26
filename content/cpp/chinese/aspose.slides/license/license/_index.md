---
title: License()
second_title: Aspose.Slides for C++ API 参考
description: 初始化此类的新实例。
type: docs
weight: 1
url: /zh/aspose.slides/license/license/
---
## License::License() 构造函数


初始化此类的新实例。

```cpp
Aspose::Slides::License::License()
```

## 备注


在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## 另见

* 类 [License](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)