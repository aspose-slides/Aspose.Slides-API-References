---
title: IMasterSlideCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 master slide 的集合。
type: docs
url: /zh-hant/com.aspose.slides/imasterslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

表示 master slide 的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 從集合中移除特定物件的第一次出現。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除指定索引處的元素。 |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 移除未使用的 master slide。 |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 在集合末端加入指定 master slide 的副本。 |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 在集合的指定位置插入指定 master slide 的副本。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

取得指定索引處的元素。唯讀 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**回傳值：**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

從集合中移除特定物件的第一次出現。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要從集合中移除的 master slide。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

從集合中移除指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

移除未使用的 master slide。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ignorePreserveField | boolean | 決定此方法是否應在 [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) 屬性設定為 true 時仍移除未使用的 master。 |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

在集合末端加入指定 master slide 的副本。相關的版面配置投影片也會一起被複製。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的 master slide。 |

**回傳值：**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已加入的投影片。

### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

在集合的指定位置插入指定 master slide 的副本。相關的版面配置投影片也會一起被複製。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的 master slide。 |

**回傳值：**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已插入的 master slide。