---
title: Pen()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 색을 나타내는 새로운 Pen 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) 생성자

지정된 색을 나타내는 새로운 [Pen](../) 객체를 생성합니다.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | const [Color](../../color/)\& | 생성되는 객체가 나타내는 펜의 색상 |

## Pen::Pen(const Color\&, float) 생성자

지정된 색과 너비를 나타내는 새로운 [Pen](../) 객체를 생성합니다.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | const [Color](../../color/)\& | 생성되는 객체가 나타내는 펜의 색상 |
| width | **float** | 생성되는 객체가 나타내는 펜의 너비 |

## Pen::Pen(const SharedPtr\<Brush\>\&) 생성자

새로운 [Pen](../) 객체를 생성하고 지정된 [Brush](../../brush/) 객체로 초기화합니다.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 생성되는 객체가 나타내는 펜의 채우기 속성을 지정하는 [Brush](../../brush/) 객체 |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) 생성자

새로운 [Pen](../) 객체를 생성하고 지정된 [Brush](../../brush/) 객체로 초기화합니다.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 생성되는 객체가 나타내는 펜의 채우기 속성을 지정하는 [Brush](../../brush/) 객체 |
| width | **float** | 생성되는 객체가 나타내는 펜의 너비 |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Color](../../color/)
* 클래스 [Pen](../)
* 클래스 [Brush](../../brush/)
* 네임스페이스 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)