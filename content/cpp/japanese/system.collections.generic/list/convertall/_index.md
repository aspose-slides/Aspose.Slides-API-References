---
title: ConvertAll()
second_title: Aspose.Slides for C++ API リファレンス
description: 異なる型に変換された要素のリストを作成します。
type: docs
weight: 352
url: /ja/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) method

異なる型に変換された要素のリストを作成します。

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| OutputType | 出力リスト要素の型です。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | アイテムの変換に使用するコンバータです。 |

### 戻り値

変換された要素の新しく作成されたリスト。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* クラス [List](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)