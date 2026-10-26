---
title: SetLicense()
second_title: Aspose.Slides C++ API 参考
description: 为组件授权。
type: docs
weight: 1
url: /zh/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) 方法

为组件授权。

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | 可以是完整或简短的文件名，或嵌入式资源的名称。使用空字符串切换到评估模式。 |
## 备注

尝试在以下位置查找许可证：

1. 显式路径。
2. 组件程序集的文件夹。
3. 客户端调用程序集的文件夹。
4. 入口程序集的文件夹。
5. 客户端调用程序集中的嵌入式资源。

**注意：**在 .NET Compact Framework 上，仅尝试在以下位置查找许可证：

1. 显式路径。
2. 客户端调用程序集中的嵌入式资源。

在本示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入式资源中查找名为 MyLicense.lic 的许可证文件。 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) 方法

为组件授权。

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含许可证的流。 |
## 备注

使用此方法从流加载许可证。

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ILicense](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)