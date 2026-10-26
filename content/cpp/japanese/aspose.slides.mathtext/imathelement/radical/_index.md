---
title: Radical()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された引数から、指定された次数の数学的根を求めます。
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) メソッド


指定された引数から、指定された次数の数学的根を求めます。

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Radical の引数 |

### 戻り値

型 [IMathRadical](../../imathradical/) の新しいインスタンス

## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) メソッド


指定された引数から、指定された次数の数学的根を求めます。

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Radical の引数 |

### 戻り値

型 [IMathRadical](../../imathradical/) の新しいインスタンス

## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathRadical](../../imathradical/)
* クラス [IMathElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)