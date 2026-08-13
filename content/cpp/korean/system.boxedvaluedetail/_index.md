---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides C++ API 참조
description: 
type: docs
weight: 287
url: /ko/system.boxedvaluedetail/
---
## 클래스

| 클래스 | 설명 |
| --- | --- |
| [Comparable](./comparable/) | IComparable<>의 간단한 구현 |
| [NonComparable](./noncomparable/) | IComparable<>를 구현하지 않는 박스형 타입을 위한 더미 기본 타입 |
## 구조체

| 구조체 | 설명 |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | 박스형 객체가 해당 인터페이스를 자체적으로 구현해야 하는지 검사하는 템플릿 프레디케이트. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/)는 [IComparable](../system/icomparable/)를 구현합니다. |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | 박스형 객체가 [IComparable](../system/icomparable/) 인터페이스를 자체적으로 구현해야 하는지 검사하는 템플릿 프레디케이트. |
## 함수

| 함수 | 설명 |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | 지정된 값을 [operator==()](../system/operator_equal_equal/)을 사용하여 동등성을 판단합니다. |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | 지정된 값을 메서드 [System::Object::Equals()](../system/object/equals/)를 사용하여 동등성을 판단합니다. |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | 두 개의 단정도 부동소수점 값을 비교합니다. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | 두 개의 배정도 부동소수점 값을 비교합니다. |