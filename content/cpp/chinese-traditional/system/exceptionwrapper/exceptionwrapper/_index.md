---
title: ExceptionWrapper()
second_title: Aspose.Slides for C++ API 參考文件
description: 構造一個不代表任何例外的 ExceptionWrapper 類別的空實例。
type: docs
weight: 14
url: /zh-hant/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) 建構式

構造一個不代表任何例外的 [ExceptionWrapper](../) 類別的空實例。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) 建構式

構造一個包含傳入指標的 [ExceptionWrapper](../) 類別的實例。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | 指向 Exception 類別實例的智慧指標。 |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) 建構式

複製建構式。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | 必須被複製的 wrapper 類別其他實例。 |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) 建構式

移動建構式。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | 必須被移動的 wrapper 類別其他實例。 |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) 建構式

將參數轉發給 Exception 類別的建構式，並建立持有新 Exception 類別實例的智慧指標。

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## 另見

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)