---
title: MathBlock()
second_title: Aspose.Slides for C++ API 참조
description: MathBlock 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() 생성자

새 [MathBlock](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## 비고

예제: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) 생성자

새 수학 블록을 만들고 지정된 요소를 넣습니다.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 블록에 넣을 수학 요소 |

## 비고

예제: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) 생성자

새 수학 블록을 만들고 지정된 요소들을 넣습니다.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | 블록에 넣을 수학 요소들 |

## 비고

예제: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [MathBlock](../)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)