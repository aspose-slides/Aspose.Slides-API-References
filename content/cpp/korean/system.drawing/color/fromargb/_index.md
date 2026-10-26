---
title: FromArgb()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 색상을 나타내는 Color 클래스의 인스턴스를 생성합니다.
type: docs
weight: 235
url: /ko/system.drawing/color/fromargb/
---
## Color::FromArgb(int) 메서드

[Color](../) 클래스의 인스턴스를 생성하여 지정된 색상을 나타냅니다.

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argb | int | 생성되는 객체가 나타낼 색상의 32비트 ARGB 값 |

### 반환값

지정된 색상을 나타내는 객체.

## Color::FromArgb(int, int, int, int) 메서드

[Color](../) 클래스의 인스턴스를 생성하여 지정된 색상을 나타냅니다.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alpha | int | 색상의 알파 구성 요소 값 |
| red | int | 색상의 빨간색 구성 요소 값 |
| green | int | 색상의 녹색 구성 요소 값 |
| blue | int | 색상의 파란색 구성 요소 값 |

### 반환값

지정된 색상을 나타내는 객체.

## Color::FromArgb(int, int, int) 메서드

[Color](../) 클래스의 인스턴스를 생성하여 알파 구성 요소가 0xFF인 지정된 색상을 나타냅니다.

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| red | int | 색상의 빨간색 구성 요소 값 |
| green | int | 색상의 녹색 구성 요소 값 |
| blue | int | 색상의 파란색 구성 요소 값 |

### 반환값

지정된 색상을 나타내는 객체.

## Color::FromArgb(int, Color) 메서드

[Color](../) 클래스의 인스턴스를 생성하여 지정된 색상을 나타냅니다.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alpha | int | 색상의 알파 구성 요소 값 |
| base_color | [Color](../) | 생성되는 객체가 나타낼 색상의 빨간색, 녹색 및 파란색 구성 요소를 나타내는 [Color](../) 객체의 인스턴스 |

### 반환값

지정된 색상을 나타내는 객체.

## 참고

* 클래스 [Color](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)