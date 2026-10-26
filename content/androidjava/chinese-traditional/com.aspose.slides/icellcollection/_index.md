---
title: ICellCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示儲存格的集合。
type: docs
url: /zh-hant/com.aspose.slides/icellcollection/
---
**所有已實作的介面:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection  
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

表示儲存格的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據其位置返回儲存格。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

根據其位置返回儲存格。唯讀 [ICell](../../com.aspose.slides/icell)。

--------------------

如果儲存格已合併，則可對多個索引返回同一個 CellEx 物件。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ICell](../../com.aspose.slides/icell)