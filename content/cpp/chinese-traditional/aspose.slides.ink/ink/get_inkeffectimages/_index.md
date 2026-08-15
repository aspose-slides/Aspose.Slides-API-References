---
title: get_InkEffectImages()
second_title: Aspose.Slides for C++ API 參考
description: 取得用於模擬墨刷視覺效果的自訂圖像集合。這些圖像在使用特定 InkEffectType 值（例如 Galaxy、Rainbow 等）渲染墨跡時會被使用。透過提供自己的圖像，您可以控制每個墨效果的顯示方式。
type: docs
weight: 14
url: /zh-hant/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() 方法


取得用於模擬墨刷視覺效果的自訂圖像集合。這些圖像在使用特定 [InkEffectType](../../inkeffecttype/) 值（例如 Galaxy、Rainbow 等）渲染墨跡時會被使用。透過提供自己的圖像，您可以控制每個墨效果的顯示方式。

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## 備註


此屬性允許以使用者自訂的紋理取代預設的墨效果紋理，當預設資產受到授權限制或在執行時無法取得時，這特別有用。

字典中的每個條目必須將 [InkEffectType](../../inkeffecttype/) 值與相應的 [IImage](../../../aspose.slides/iimage/) 物件（例如 Bitmap，或 **Aspose** 影像介面）關聯起來。

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## 另請參閱

* 列舉 [InkEffectType](../../inkeffecttype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDictionary](../../../system.collections.generic/idictionary/)
* 類別 [IImage](../../../aspose.slides/iimage/)
* 類別 [Ink](../)
* 命名空間 [Aspose::Slides::Ink](../../)
* 函式庫 [Aspose.Slides](../../../)