---
title: SetLicense()
second_title: Aspose.Slides C++ API 参考
description: 为组件授权。
type: docs
weight: 14
url: /zh/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) 方法

为组件授权。

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | 可以是完整或简短的文件名，或嵌入资源的名称。使用空字符串可切换为评估模式。 |

## 备注

尝试在以下位置查找许可证：

1. 明确的路径。

2. 组件程序集所在的文件夹。

3. 客户端调用程序集所在的文件夹。

4. 入口程序集所在的文件夹。

5. 客户端调用程序集中的嵌入资源。

**注意:** 在 .NET Compact Framework 上，仅在以下位置查找许可证：

1. 明确的路径。

2. 客户端调用程序集中的嵌入资源。

在本示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) 方法

为组件授权。

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含许可证的流。 |

## 备注

使用此方法从流加载许可证。

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [License](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)