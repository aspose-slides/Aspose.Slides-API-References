---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides for C++ API 參考
description: "此屬性定義 Presentation 類別的執行個體在其生命週期內是否可以成為來源（檔案或串流）的擁有者。若執行個體是擁有者，則會鎖定來源。這有助於在處理 BLOB 時改善記憶體使用量與效能，但在 Presentation 的執行個體生命週期內，來源（串流或檔案）無法被變更。以下是一個範例："
type: docs
weight: 1
url: /zh-hant/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() 方法

此屬性定義在 [Presentation](../../presentation/) 類別的執行個體於其生命週期內是否可成為來源（檔案或串流）的擁有者。若執行個體是擁有者，則會鎖定來源。這有助於在處理 BLOB 時改善記憶體使用量與效能，但在 [Presentation](../../presentation/) 的執行個體生命週期內，來源（串流或檔案）無法被變更。以下為範例：

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## 備註

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // 將拋出 IOException，因為 pres.pptx 在 Presentation 的生命週期內被鎖定
    // File::Delete(u"pres.pptx");
}
// 在 Presentation 物件被銷毀後，檔案解鎖且可以被刪除
IO::File::Delete(u"pres.pptx");
```

## 另請參閱

* 列舉 [PresentationLockingBehavior](../../presentationlockingbehavior/)
* 類別 [IBlobManagementOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)