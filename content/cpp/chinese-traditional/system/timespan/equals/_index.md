---
title: Equals()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷目前物件所表示的時間間隔是否等於指定物件所表示的時間間隔。
type: docs
weight: 40
url: /zh-hant/system/timespan/equals/
---
## TimeSpan::Equals(TimeSpan) const 方法


判斷目前物件所表示的時間間隔是否等於指定物件所表示的時間間隔。

```cpp
constexpr bool System::TimeSpan::Equals(TimeSpan value) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [TimeSpan](../) | 與目前物件比較的 [TimeSpan](../) 物件 |

### 傳回值

True if the current object and the specified object represent the same time interval, otherwise - false

## TimeSpan::Equals(const SharedPtr\<Object\>\&) const 方法


判斷目前物件所表示的時間間隔是否等於指定物件所表示的時間間隔。

```cpp
bool System::TimeSpan::Equals(const SharedPtr<Object> &obj) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 與目前物件比較的 [TimeSpan](../) 物件 |

### 傳回值

True if the current object and the specified object represent the same time interval, otherwise - false

## TimeSpan::Equals(TimeSpan, TimeSpan) 方法


如果指定的物件表示相同的時間間隔則傳回 true，否則傳回 false。

```cpp
static constexpr bool System::TimeSpan::Equals(TimeSpan a, TimeSpan b)
```

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)