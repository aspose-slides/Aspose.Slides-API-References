---
title: LoadingStreamBehavior
second_title: Aspose.Slides C++ API 参考
description: "System::IO::Stream 传递给方法时被视为二进制大对象 (BLOB)（参见 IBlobManagementOptions 描述）。此枚举的值标识当 System::IO::Stream 被传递给方法时应如何处理。根据需求，可以做出不同的决定以提供最高效的行为。"
type: docs
weight: 6735
url: /zh/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior 枚举

传递给方法的 [System::IO::Stream](../../system.io/stream/) 被视为二进制大对象（BLOB）（参见 [IBlobManagementOptions](../iblobmanagementoptions/) 描述）。此枚举的值标识当 [System::IO::Stream](../../system.io/stream/) 被传递给方法时应如何处理。根据需求，可以做出不同的决定以提供最高效的行为。

```cpp
enum class LoadingStreamBehavior
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | 流将被读取至结束，然后释放——即保证该流在将来不会被 [IPresentation](../ipresentation/) 实例使用。它可以被客户端代码关闭或以其他任何方式使用。 |
| KeepLocked | 1 | 流将在 [IPresentation](../ipresentation/) 对象内部被锁定，即流的所有权将被转移。[IPresentation](../ipresentation/) 对象将在其自身被释放时负责正确处理该流。当需要序列化大型 BLOB 文件（例如大型视频或音频——参见 [IBlobManagementOptions](../iblobmanagementoptions/) 描述）并希望防止将该文件加载到内存或出现其他性能问题时，此行为极其有用。您只需为该文件打开 [System::IO::FileStream](../../system.io/filestream/) 并将其传递给方法，选择 [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior。 |

## 另请参阅

* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)