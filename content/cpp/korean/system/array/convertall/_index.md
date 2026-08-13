---
title: ConvertAll()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 변환자 대리자를 사용하여 지정된 배열의 요소를 OutputType 유형으로 변환한 후, 새 Array 객체를 생성하고 해당 요소들로 채웁니다.
type: docs
weight: 625
url: /ko/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) 메서드


새로운 [Array](../) 객체를 생성하고 지정된 배열의 요소를 지정된 변환자(delegate)를 사용하여 **OutputType** 유형으로 변환한 요소로 채웁니다.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| InputType | 입력 배열 요소의 유형 |
| OutputType | 결과 배열 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | [Array](../) 객체 |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | 입력 배열의 각 요소를 **OutputType** 유형의 동등한 값으로 변환하는 Converter 객체 |

### 반환 값

새로운 배열로, **input_array**의 값에 해당하는 **OutputType** 유형의 값을 포함합니다.

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) 메서드


새로운 [Array](../) 객체를 생성하고 지정된 배열의 요소를 지정된 변환 함수 객체를 사용하여 **OutputType** 유형으로 변환한 요소로 채웁니다.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| InputType | 입력 배열 요소의 유형 |
| OutputType | 결과 배열 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | [Array](../) 객체 |
| converter | std::function\<OutputType(InputType)> | 입력 배열의 각 요소를 **OutputType** 유형의 동등한 값으로 변환하는 함수 객체 |

### 반환 값

새로운 배열로, **input_array**의 값에 해당하는 **OutputType** 유형의 값을 포함합니다.

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)