---
title: Hyperlink()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個超連結的實例。
type: docs
weight: 339
url: /zh-hant/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) 建構函式


建立一個超連結的實例。

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) 建構函式


建立指向特定投影片的超連結實例。註：建立的超連結應指派給同一簡報中的某個物件，否則連結將儲存為 NoAction。

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Target slide. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) 建構函式


使用其他超連結作為來源、覆寫次要屬性，建立超連結實例。

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Source hyperlink |
| targetFrame | [System::String](../../../system/string/) | Target frame |
| tooltip | [System::String](../../../system/string/) | Tooltip text |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Hyperlink](../)
* Class [ISlide](../../islide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)