---
title: Dictionary()
second_title: Aspose.Slides for C++ API 참조
description: 빈 사전을 생성합니다.
type: docs
weight: 1
url: /ko/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() 생성자

빈 사전을 생성합니다.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) 생성자

맵에서 데이터를 복사합니다.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | 복사할 맵. |

## Dictionary::Dictionary(int) 생성자

미리 할당된 사전을 생성하는 오버로드이며 실제로는 할당을 수행하지 않습니다.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| capacity | int | 할당할 용량; 무시됩니다. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) 생성자

복사 생성자.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../)를 복사할 원본. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) 생성자

복사 생성자.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | 원본 사전. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) 객체를 사용합니다. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) 생성자

빈 사전을 생성합니다.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/)를 사용합니다. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) 생성자

빈 사전을 생성합니다.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| capacity | int | [Dictionary](../) 생성 후 용량; 무시됩니다. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/)를 사용합니다. |

## 참고

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Dictionary](../)
* 클래스 [IDictionary](../../idictionary/)
* 클래스 [IEqualityComparer](../../iequalitycomparer/)
* 네임스페이스 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)