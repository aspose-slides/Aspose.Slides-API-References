---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides C++ API 參考文件
description: "此屬性定義了 Presentation 類的實例在其生命週期內是否可以成為來源（檔案或串流）的擁有者。如果實例是擁有者，則會鎖定來源。這有助於在處理 BLOB 時降低記憶體消耗與提升效能，但在 Presentation 的實例生命週期內，來源（串流或檔案）無法變更。以下是一個範例："
type: docs
weight: 14
url: /zh-hant/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) 方法

此屬性定義了 [Presentation](../../presentation/) 類的實例在其生命週期內是否可以成為來源（檔案或串流）的擁有者。如果實例是擁有者，則會鎖定來源。這有助於在處理 BLOB 時降低記憶體消耗與提升效能，但在 [Presentation](../../presentation/) 的實例生命週期內，來源（串流或檔案）無法變更。以下是一個範例：

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## 備註

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // 因為 pres.pptx 在 Presentation 生命週期內被鎖定，將拋出 IOException
    // File::Delete(u"pres.pptx");
}
// 在 Presentation 物件銷毀後，檔案會解鎖且可以被刪除
IO::File::Delete(u"pres.pptx");
```

## 另見

* 列舉 [PresentationLockingBehavior](../../presentationlockingbehavior/)
* 類別 [IBlobManagementOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)