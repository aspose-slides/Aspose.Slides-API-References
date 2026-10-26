---
title: PresentationLockingBehavior
second_title: Aspose.Slides for C++ API 参考
description: "表示在加载并使用 IPresentation 实例时，处理 IPresentation 源（文件或 System::IO::Stream）的行为。"
type: docs
weight: 6748
url: /zh/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior 枚举

表示在加载并使用 [IPresentation](../ipresentation/) 实例时，处理 [IPresentation](../ipresentation/) 源（文件或 [System::IO::Stream](../../system.io/stream/)）的行为。

```cpp
enum class PresentationLockingBehavior
```

### 值

| 名称 | 值 | 说明 |
| --- | --- | --- |
| LoadAndRelease | 0 | 该源仅在 [IPresentation](../ipresentation/) 构造函数执行期间被锁定。 |
| KeepLocked | 1 | 该源将在 [IPresentation](../ipresentation/) 实例的整个生命周期内被锁定，直至其被释放。 |

## 备注

源是传递给 [IPresentation](../ipresentation/) 构造函数的参数。在下面的示例中，源是 "pres.pptx" 文件：

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

对于此示例，源（"pres.pptx" 文件）将在 [IPresentation](../ipresentation/) 实例的生命周期内被锁定，即其他进程无法更改或删除它。 

## 另见

* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)