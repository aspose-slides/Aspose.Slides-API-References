---
title: Radical()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された引数から、指定された次数の数学的根を指定します。
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) メソッド


指定された引数から、指定された次数の数学的根を指定します。

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Radical の引数 |

### 戻り値

型 [IMathRadical](../../imathradical/) の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) メソッド


指定された引数から、指定された次数の数学的根を指定します。

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```


### 引数

| パラメータ | 型 | 説明 |
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

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathRadical](../../imathradical/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathElementBase](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)