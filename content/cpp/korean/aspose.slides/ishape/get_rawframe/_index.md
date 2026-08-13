---
title: get_RawFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 원시 도형 프레임의 속성을 반환합니다. IShapeFrame을 읽으세요.
type: docs
weight: 40
url: /ko/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() 메서드

원시 도형 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## 비고

정의되지 않은 프레임을 [IShape::set_Frame](../set_frame/)에 할당하려는 코드는 일반적인 경우에 의미가 없으며(특히 상위 [GroupShape](../../groupshape/)가 다른 GroupShape에 여러 번 중첩된 경우), 예를 들어: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
또는 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
이러한 코드는 모호한 상황을 초래할 수 있습니다. 따라서 [IShape::set_Frame](../set_frame/)에 대해 정의되지 않은 값을 사용하는 것을 제한하는 규칙이 추가되었습니다. x, y, width, height, flipH, flipV 및 rotationAngle 값은 정의되어 있어야 합니다( std::numeric_limits<float>::quiet_NaN() 이거나 [NullableBool::NotDefined](../../nullablebool/) 가 아니어야 함). 위의 예제 코드는 이제 ArgumentException 예외를 발생시킵니다. 이는 다음 사용 사례에 적용됩니다: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // 정의되지 않을 수 없습니다

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height 매개변수는 std::numeric_limits<float>::quiet_NaN()일 수 없습니다:
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```

그러나 [IShape::set_RawFrame](../set_rawframe/) 메서드에 대한 프레임은 정의되지 않을 수 있습니다. 이는 도형이 자리 표시자에 연결된 경우 의미가 있습니다. 이때 정의되지 않은 도형 프레임 값은 상위 자리 표시자 도형에서 재정의됩니다. 해당 도형에 상위 자리 표시자 도형이 없으면 그 도형은 [IShape::get_RawFrame](./)에 따라 유효 프레임을 계산할 때 기본값을 사용합니다. x, y, width, height, flipH, flipV 및 rotationAngle에 대한 기본값은 0과 [NullableBool::False](../../nullablebool/) 입니다. 예를 들어: 
```cpp
SharedPtr<IShape> shape = ...; // shape은 placeholder에 연결됩니다
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // 이제 shape은 placeholder에서 x, y, height, flipH, flipV 값을 상속받으며 width=100과 rotationAngle=0을 재정의합니다.
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShapeFrame](../../ishapeframe/)
* 클래스 [IShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)