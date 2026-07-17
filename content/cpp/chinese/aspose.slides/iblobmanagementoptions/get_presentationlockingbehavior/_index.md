---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides C++ API 参考
description: "此属性定义 Presentation 类的实例在实例生命周期内是否可以成为源（文件或流）的所有者。如果实例是所有者，它会锁定源。这有助于在处理 BLOB 时提升内存使用和性能，但在 Presentation 实例的生命周期内，源（流或文件）无法更改。这是一个示例："
type: docs
weight: 1
url: /zh/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() 方法

此属性定义 [Presentation](../../presentation/) 类的实例在实例生命周期内是否可以成为源（文件或流）的所有者。如果实例是所有者，它会锁定源。这有助于在处理 BLOB 时提高内存使用和性能，但在 [Presentation](../../presentation/) 的实例生命周期期间，源（流或文件）无法更改。这是一个示例：

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## 备注

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // 将抛出 IOException，因为 pres.pptx 在整个 Presentation 生命周期内被锁定
    // File::Delete(u"pres.pptx");
}
// 在 Presentation 对象销毁后，文件已解锁并且可以被删除
IO::File::Delete(u"pres.pptx");
```

## 另见

* 枚举 [PresentationLockingBehavior](../../presentationlockingbehavior/)
* 类 [IBlobManagementOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)