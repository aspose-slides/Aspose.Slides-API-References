---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 将 cookie 添加到集合中。
type: docs
weight: 105
url: /zh/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) 方法

将 cookie 添加到集合中。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 要添加的 cookie。 |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) 方法

将 cookie 添加到集合中。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 要添加的 cookie。 |
| throwOnError | **bool** | 指示在发生错误时是否会抛出异常的值。 |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) 方法

将指定集合中的 cookie 复制到当前集合。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | 将从中复制 cookie 的集合。 |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) 方法

为指定的 URI 添加 cookie。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Cookie 的 URI。 |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 要添加的 cookie。 |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) 方法

将指定集合中对应指定 URI 的 cookie 复制到当前集合。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Cookie 的 URI。 |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | 必须从中复制 cookie 的 cookie 集合。 |

## 另请参阅

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [Cookie](../../cookie/)
* 类 [CookieContainer](../)
* 类 [CookieCollection](../../cookiecollection/)
* 类 [Uri](../../../system/uri/)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)