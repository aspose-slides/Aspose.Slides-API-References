---
title: WebProxy()
second_title: Aspose.Slides لمرجع API C++
description: ينشئ مثيلًا جديدًا.
type: docs
weight: 131
url: /ar/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | عنوان خادم الوكيل. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | عنوان خادم الوكيل. |
| BypassOnLocal | **bool** | قيمة تشير إلى ما إذا كان يجب استخدام خادم الوكيل للعناوين المحلية. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | عنوان خادم الوكيل. |
| BypassOnLocal | **bool** | قيمة تشير إلى ما إذا كان يجب استخدام خادم الوكيل للعناوين المحلية. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | قائمة العناوين التي لا تستخدم خادم الوكيل. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | عنوان خادم الوكيل. |
| BypassOnLocal | **bool** | قيمة تشير إلى ما إذا كان يجب استخدام خادم الوكيل للعناوين المحلية. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | قائمة العناوين التي لا تستخدم خادم الوكيل. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | بيانات الاعتماد التي تُرسل إلى خادم الوكيل للمصادقة. |

## WebProxy::WebProxy(String, int32_t) منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| Host | [String](../../../system/string/) | اسم المضيف. |
| Port | **int32_t** | رقم المنفذ. |

## WebProxy::WebProxy(String) منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| Address | [String](../../../system/string/) | عنوان خادم الوكيل. |

## WebProxy::WebProxy(String, bool) منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| Address | [String](../../../system/string/) | عنوان خادم الوكيل. |
| BypassOnLocal | **bool** | قيمة تشير إلى ما إذا كان يجب استخدام خادم الوكيل للعناوين المحلية. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| Address | [String](../../../system/string/) | عنوان خادم الوكيل. |
| BypassOnLocal | **bool** | قيمة تشير إلى ما إذا كان يجب استخدام خادم الوكيل للعناوين المحلية. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | قائمة العناوين التي لا تستخدم خادم الوكيل. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) منشئ

ينشئ مثيلًا جديدًا.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| Address | [String](../../../system/string/) | عنوان خادم الوكيل. |
| BypassOnLocal | **bool** | قيمة تشير إلى ما إذا كان يجب استخدام خادم الوكيل للعناوين المحلية. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | قائمة العناوين التي لا تستخدم خادم الوكيل. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | بيانات الاعتماد التي تُرسل إلى خادم الوكيل للمصادقة. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)