---
title: ICellCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示儲存格的集合。
type: docs
url: /zh-hant/com.aspose.slides/icellcollection/
---
**已實作的介面:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

表示儲存格的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據其位置返回儲存格。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


根據其位置返回儲存格。唯讀 [ICell](../../com.aspose.slides/icell).

--------------------

在儲存格合併的情況下，一個 CellEx 物件可能會對多個索引返回。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[ICell](../../com.aspose.slides/icell)