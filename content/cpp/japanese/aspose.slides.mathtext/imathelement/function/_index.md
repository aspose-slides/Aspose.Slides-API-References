---
title: Function()
second_title: Aspose.Slides for C++ API リファレンス
description: このインスタンスを関数名として使用し、引数の関数を取得します
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) メソッド


このインスタンスを関数名として使用し、引数の関数を取得します

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 関数の引数 |

### 戻り値

型 [IMathFunction](../../imathfunction/) の新しい数式要素
## 備考



例: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) メソッド


このインスタンスを関数名として使用し、引数の関数を取得します

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | 関数の引数 |

### 戻り値

型 [IMathFunction](../../imathfunction/) の新しい数式要素
## 備考



例: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathFunction](../../imathfunction/)
* クラス [IMathElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)