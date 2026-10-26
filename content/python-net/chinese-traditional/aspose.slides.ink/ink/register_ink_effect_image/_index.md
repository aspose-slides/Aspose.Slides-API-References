---
title: register_ink_effect_image method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
將影像註冊至用於模擬墨筆視覺效果的自訂影像集合中。
            這些影像會在使用特定 [`InkEffectType`](/slides/python-net/zh-hant/aspose.slides.ink/inkeffecttype) 值呈現墨跡時使用，例如 Galaxy、Rainbow 等。透過提供自己的影像，您可以控制每種墨筆效果的呈現方式。

```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/zh-hant/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage) |  |

### 備註

此方法允許以使用者自訂的貼圖取代預設的墨筆效果紋理，這在預設資產受授權限制或於執行時無法取得時特別有用。
            每個註冊的值對必須將 [`InkEffectType`](/slides/python-net/zh-hant/aspose.slides.ink/inkeffecttype) 值與相應的 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage) 物件（例如 Bitmap，或 Aspose 影像介面）關聯起來。

### 另見
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`Ink`](/slides/python-net/zh-hant/aspose.slides.ink/ink)
* 列舉 [`InkEffectType`](/slides/python-net/zh-hant/aspose.slides.ink/inkeffecttype)
* 模組 [`aspose.slides.ink`](/slides/python-net/zh-hant/aspose.slides.ink)
* 函式庫 [`Aspose.Slides`](/slides/python-net)