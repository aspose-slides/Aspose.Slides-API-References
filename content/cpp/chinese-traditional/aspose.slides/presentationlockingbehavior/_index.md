---
title: PresentationLockingBehavior
second_title: Aspose.Slides for C++ API 參考文件
description: "代表在載入並使用 IPresentation 實例時，對 IPresentation 來源（檔案或 System::IO::Stream）的處理行為。"
type: docs
weight: 6748
url: /zh-hant/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior 列舉

表示在載入並使用 [IPresentation](../ipresentation/) 的實例時，對 [IPresentation](../ipresentation/) 來源（檔案或 [System::IO::Stream](../../system.io/stream/)）的處理行為。

```cpp
enum class PresentationLockingBehavior
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| LoadAndRelease | 0 | 在 [IPresentation](../ipresentation/) 建構函式執行期間，來源將僅被鎖定。 |
| KeepLocked | 1 | 來源將在 [IPresentation](../ipresentation/) 實例的整個生命週期內被鎖定，直至其被釋放。 |

## 備註

來源是傳遞給 [IPresentation](../ipresentation/) 建構函式的參數。以下範例中，來源是 \"pres.pptx\" 檔案：

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

在此範例中，來源（\"pres.pptx\" 檔案）將在 [IPresentation](../ipresentation/) 實例的生命週期內被鎖定，也就是說其他程序無法變更或刪除它。

## 另請參閱

* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)