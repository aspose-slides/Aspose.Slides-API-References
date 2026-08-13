---
title: AddZoomFrame()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 새 Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 92
url: /ko/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) 메서드


새 Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 새 Zoom 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 새 Zoom 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 새 Zoom 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 새 Zoom 프레임의 높이이며, 단위는 포인트입니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 프레임이 참조하는 [ISlide](../../islide/); 이 프레젠테이션에 속해야 합니다. |

### 반환값

새로 생성된 [IZoomFrame](../../izoomframe/).
## 비고


이 예제는 컬렉션의 끝에 Zoom 객체를 추가하는 방법을 보여줍니다 (\"Presentation.pptx\" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정합니다): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) 메서드


새 Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 새 Zoom 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 새 Zoom 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 새 Zoom 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 새 Zoom 프레임의 높이이며, 단위는 포인트입니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 프레임이 참조하는 [ISlide](../../islide/); 이 프레젠테이션에 속해야 합니다. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 참조된 슬라이드 [IPPImage](../../ippimage/)의 이미지. |

### 반환값

새로 생성된 [IZoomFrame](../../izoomframe/).
## 비고


이 예제는 컬렉션의 끝에 Zoom 객체를 추가하는 방법을 보여줍니다 (\"Presentation.pptx\" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정합니다): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)