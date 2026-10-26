---
title: MathBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: MathBlock クラスの新しいインスタンスを初期化します。
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() コンストラクタ

[MathBlock](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## 備考

例:  
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) コンストラクタ

新しい数式ブロックを作成し、指定された要素をその中に入れます。

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ブロックに入れる数式要素 |
## 備考

例:  
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) コンストラクタ

新しい数式ブロックを作成し、指定された要素を複数入れます。

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | ブロックに入れる数式要素の集合 |
## 備考

例:  
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [MathBlock](../)
* クラス [IMathElement](../../imathelement/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)