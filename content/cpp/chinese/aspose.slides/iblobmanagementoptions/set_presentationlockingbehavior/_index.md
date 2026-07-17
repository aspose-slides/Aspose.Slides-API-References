---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides for C++ API 参考
description: "此属性定义在实例生命周期内，Presentation 类的实例是否可以成为源 - 文件或流的所有者。如果实例是所有者，它会锁定源。这有助于在使用 BLOB 时提升内存消耗和性能，但在 Presentation 的实例生命周期内，源（流或文件）无法更改。这是一个示例："
type: docs
weight: 14
url: /zh/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) 方法


此属性定义在实例生命周期内，[Presentation](../../presentation/) 类的实例是否可以成为源 - 文件或流的所有者。如果实例是所有者，它会锁定源。这有助于在使用 BLOB 时提升内存消耗和性能，但在 [Presentation](../../presentation/) 的实例生命周期内，源（流或文件）无法更改。这是一个示例：

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## 备注



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // 因为 pres.pptx 在 Presentation 生命周期内被锁定，将抛出 IOException
    // File::Delete(u"pres.pptx");
}
// 在 Presentation 对象销毁后，文件被解锁，且可以被删除
IO::File::Delete(u"pres.pptx");
```

## 另请参阅

* 枚举 [PresentationLockingBehavior](../../presentationlockingbehavior/)
* 类 [IBlobManagementOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)