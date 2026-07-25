---
title: WeakReference()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトコンストラクタ。
type: docs
weight: 1
url: /ja/system/weakreference_tmpl_t__end_tmpl/weakreference/
---
## WeakReference< T >::WeakReference() メソッド

デフォルトコンストラクタ。

```cpp
System::WeakReference<T>::WeakReference()
```

## WeakReference< T >::WeakReference(std::nullptr_t) メソッド

nullptr からのコンストラクタ。

```cpp
System::WeakReference<T>::WeakReference(std::nullptr_t)
```

## WeakReference< T >::WeakReference(const SmartPtr\<T\>\&) メソッド

WeakReference クラスの新しいインスタンスを初期化し、指定されたオブジェクトを参照します。

```cpp
System::WeakReference<T>::WeakReference(const SmartPtr<T> &data)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<T\>\& | [Object](../../object/) を格納します。 |

## WeakReference< T >::WeakReference(const SmartPtr\<T\>\&, bool) メソッド

WeakReference クラスの新しいインスタンスを初期化し、指定されたオブジェクトを参照します。

```cpp
System::WeakReference<T>::WeakReference(const SmartPtr<T> &data, bool trackResurrection)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<T\>\& | [Object](../../object/) を格納します。 |
| trackResurrection | **bool** | 無視されます。 |

## 参照

* クラス [WeakReference< T >](../)
* クラス [SmartPtr](../../smartptr/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)