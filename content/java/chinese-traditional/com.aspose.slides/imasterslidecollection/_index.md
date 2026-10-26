---
title: IMasterSlideCollection
second_title: Aspose.Slides Java API 參考
description: 表示一個母片投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/imasterslidecollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

表示一個母片投影片的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 從集合中移除第一個符合的特定物件。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除指定索引處的元素。 |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 移除未使用的母片投影片。 |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 將指定的母片投影片的副本新增至集合的末端。 |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 將指定的母片投影片的副本插入集合的指定位置。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

取得指定索引處的元素。唯讀 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**回傳值:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

從集合中移除第一個符合的特定物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要從集合中移除的母片投影片。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

從集合中移除指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

移除未使用的母片投影片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ignorePreserveField | boolean | 判斷此方法是否應移除未使用的母片，即使其 [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) 屬性被設為 true。 |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

將指定的母片投影片的副本新增至集合的末端。相關聯的版面配置投影片也會一併複製。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要複製的投影片。 |

**回傳值:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已新增的投影片。
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

將指定的母片投影片的副本插入集合的指定位置。相關聯的版面配置投影片也會一併複製。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要複製的投影片。 |

**回傳值:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已插入的母投影片。