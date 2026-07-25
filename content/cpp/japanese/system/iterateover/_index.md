---
title: IterateOver()
second_title: Aspose.Slides for C++ APIリファレンス
description: "この関数プロパティは enumerable（または iterable）オブジェクトをラップし、range-based for ループで使用できるようにします。このオーバーロードは begin()、end() メソッドを持たない Enumerable に対して、target 型引数を指定して (auto& value : IterateOver<SomeType>(enumerable)) と使用します。"
type: docs
weight: 2471
url: /ja/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) 関数

この関数プロパティは enumerable（または iterable）オブジェクトをラップし、range-based for ループで使用できるようにします。このオーバーロードは begin()、end() メソッドを持たない Enumerable に対して、target 型引数を指定して (auto& value : IterateOver<SomeType>(enumerable)) のように使用します。

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | ターゲット型で、イテレータから返される必要があります |
| Enumerable | ラップされたオブジェクトの型 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 関数

この関数プロパティは enumerable（または iterable）オブジェクトをラップし、range-based for ループで使用できるようにします。このオーバーロードは begin()、end() メソッドを持たない Enumerable に対して、デフォルトの target 型引数で (auto& value : IterateOver(enumerable)) と使用でき、以下の C# コード foreach (var value in enumerable) と同等です。

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Enumerable | ラップされたオブジェクトの型 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 関数

この関数プロパティは enumerable（または iterable）オブジェクトをラップし、range-based for ループで使用できるようにします。このオーバーロードは begin()、end() メソッドを持つ Enumerable に対して、デフォルトの target 型引数で (auto& value : IterateOver(enumerable)) と使用します。

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Enumerable | ラップされたオブジェクトの型 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 関数

この関数プロパティは enumerable（または iterable）オブジェクトをラップし、range-based for ループで使用できるようにします。このオーバーロードは begin()、end() メソッドを持つ Enumerable に対して、target 型がイテレータの元の value_type と同じの場合に使用します。

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Enumerable | ラップされたオブジェクトの型 |
| T | イテレータから返される必要がある target 型 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 関数

この関数プロパティは enumerable（または iterable）オブジェクトをラップし、range-based for ループで使用できるようにします。このオーバーロードは begin()、end() メソッドを持つ Enumerable に対して、target 型がイテレータの元の value_type と異なる場合に使用します。

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Enumerable | ラップされたオブジェクトの型 |
| T | イテレータから返される必要がある target 型 |

## System::IterateOver(const Enumerable *) 関数

この関数プロパティは enumerable（または iterable）オブジェクトをラップし、range-based for ループで使用できるようにします。このオーバーロードは Enumerable に対してデフォルトの target 型を使用します。

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Enumerable | ラップされたオブジェクトの型 |

## System::IterateOver(const Enumerable *) 関数

この関数プロパティは enumerable（または iterable）オブジェクトをラップし、range-based for ループで使用できるようにします。このオーバーロードは begin()、end() メソッドを持たない Enumerable に対して、target 型引数を指定して (auto& value : IterateOver<SomeType>(enumerable)) のように使用します。

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | ターゲット型で、イテレータから返される必要があります |
| Enumerable | ラップされたオブジェクトの型 |

## 参照

* クラス [SmartPtr](../smartptr/)
* 構造体 [IsSmartPtr](../issmartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)