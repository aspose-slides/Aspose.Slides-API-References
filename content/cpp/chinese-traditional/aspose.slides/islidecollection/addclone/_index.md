---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考
description: 將指定投影片的副本新增至集合的末端。
type: docs
weight: 14
url: /zh-hant/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) 方法

將指定投影片的副本添加至集合的末端。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 要克隆。 |

### 回傳值

新投影片。

## 備註

在不同簡報之間克隆投影片時，投影片的母版也可能被克隆。內部註冊表用於追蹤自動克隆的母版，以防止同一母版投影片產生多個克隆。手動克隆母版投影片既不會被阻止，也不會被註冊。若需要對克隆過程有更精細的控制，請使用 [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) 或 [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) 來克隆投影片，使用 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) 或 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) 來克隆版面配置，並使用 [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) 來克隆母版。 

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) 方法

將指定投影片的副本添加至指定章節的末端。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 要克隆。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 用於新投影片。 |

### 回傳值

新投影片。

## 備註

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// 現在第二個章節包含第一張投影片的副本。
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) 方法

將指定投影片的副本添加至集合的末端。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 要克隆。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 用於新投影片的版面配置。 |

### 回傳值

新投影片。

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) 方法

將指定來源投影片的副本添加至集合的末端。會自動從指定的母版中選取適當的版面配置（適當的版面配置是與來源投影片版面配置具有相同 Type 或 Name 的版面配置）。如果在指定的母版中沒有相應的版面配置，則會克隆來源投影片的版面配置（若 allowCloneMissingLayout 為 true），否則會拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 要克隆。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新投影片的母版投影片。 |
| allowCloneMissingLayout | **bool** | 如果在指定的母版中沒有相應的版面配置，則會克隆來源投影片的版面配置（若 allowCloneMissingLayout 為 true），否則會拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |

### 回傳值

新投影片。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlide](../../islide/)
* 類別 [ISlideCollection](../)
* 類別 [ISection](../../isection/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [IMasterSlide](../../imasterslide/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)