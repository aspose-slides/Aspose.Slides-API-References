---
title: SmartPtr()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立所需模式的 SmartPtr 物件。
type: docs
weight: 1
url: /zh-hant/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) 建構函式

建立所需模式的 [SmartPtr](../) 物件。

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | 指標模式。 |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) 建構函式

建立所需模式的空指標 [SmartPtr](../) 物件。

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mode | std::nullptr_t | 指標模式。 |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) 建構函式

建立指向指定物件的 [SmartPtr](../)，或將原始指標轉換為 [SmartPtr](../)。

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | 被指向的物件。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指標模式。 |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) 建構函式

複製建構 [SmartPtr](../) 物件。之後兩個指標指向相同的物件。

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | 要複製的指標。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指標模式。 |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) 建構函式

複製建構 [SmartPtr](../) 物件。之後兩個指標指向相同的物件。若允許，則執行型別轉換。

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Q | x 所指向物件的型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | 要複製的指標。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指標模式。 |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) 建構函式

移動建構 [SmartPtr](../) 物件。實際上，若兩個指標模式相同，會交換兩者。呼叫後 x 可能無法使用。

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 要移動的指標。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指標模式。 |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) 建構函式

透過建立不同型別的新陣列，轉換被參考陣列的型別。若 C# 中有 C++ 不支援的陣列型別轉換時，此功能很有用。

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Y | 來源陣列的型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | 指向要建立副本的陣列，但元素型別不同。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指標模式。 |

## SmartPtr::SmartPtr(const Y\&) 建構函式

初始化空陣列。用於翻譯某些 C# 程式碼結構。

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Y | EmptyArrayInitializer 型別的佔位符。 |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) 建構函式

建構一個與 ptr 初始值共享所有權資訊的 [SmartPtr](../)，但持有不相關且未受管理的指標 p。

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | 另一個智慧指標，與之共享所有權。 |
| p | [Pointee_](../pointee_/) * | 要管理的物件指標。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指標模式。 |
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// 此類別包含一個將被列印的欄位。
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// 此類別包含 Foo 類別的實例。
class Bar : public System::Object
{
public:
  Foo data;
};

// 用於從 Foo 類別實例列印字串。
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// 列印指向該物件的共享指標數量。
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // 建立指向 Bar 類別實例的 SharedPtr。
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // 建立指向 Bar 類別實例欄位的 SharedPtr。
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // 使 'bar' 指標指向 nullptr。
  bar.reset();
  PrintSharedCount(bar);
  // bar->data 仍然存在且 'foo' 指標有效。
  PrintMessage(foo);

  return 0;
}
/*
此程式範例會產生以下輸出：
共享指標的數量: 1
共享指標的數量: 2
共享指標的數量: 0
哈囉，世界！
*/
```

## 另請參閱

* 列舉 [SmartPtrMode](../../smartptrmode/)
* 型別別名 [Pointee_](../pointee_/)
* 型別別名 [SmartPtr_](../smartptr_/)
* 類別 [SmartPtr](../)
* 類別 [Array](../../array/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)