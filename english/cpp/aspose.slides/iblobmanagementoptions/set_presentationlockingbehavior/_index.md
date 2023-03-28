---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides for C++ API Reference
description: "This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps to improve memory consumption and performance while working with BLOBs, but the source (stream or file) can't be changed during Presentation's instance lifetime. This is an example:"
type: docs
weight: 14
url: /cpp/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior([Aspose::Slides::PresentationLockingBehavior](../../presentationlockingbehavior/)) method


This property defines if an instance of the [Presentation](../../presentation/) class can be an owner of the source - file or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps to improve memory consumption and performance while working with BLOBs, but the source (stream or file) can't be changed during [Presentation](../../presentation/)'s instance lifetime. This is an example:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Remarks



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException will be thrown because pres.pptx is locked for a Presentation lifetime
    // File::Delete(u"pres.pptx");
}
// after Presentation object destroyed, file is unlocked and can be deleted
IO::File::Delete(u"pres.pptx");
```

## See Also

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Class [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
