---
title: CreateHttp()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URI kullanılarak WebRequest sınıfının yeni bir örneği oluşturulur.
type: docs
weight: 79
url: /tr/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) yöntemi


Belirtilen URI kullanılarak [WebRequest](../) sınıfının yeni bir örneğini oluşturur.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | Yeni bir [WebRequest](../) sınıfının oluşturulması için kullanılan URI. |

### Dönüş Değeri

Yeni oluşturulmuş WebRequest-sınıf örneği.
## Açıklamalar



Belirtilen URI, [http://](http://) veya [https://](https://) dışındaki herhangi bir şema ile başlarsa NotSupportedException fırlatılacaktır. 

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) yöntemi


Belirtilen URI kullanılarak [WebRequest](../) sınıfının yeni bir örneğini oluşturur.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Yeni bir [WebRequest](../) sınıfının oluşturulması için kullanılan URI. |

### Dönüş Değeri

Yeni oluşturulmuş WebRequest-sınıf örneği.
## Açıklamalar



Belirtilen URI, [http://](http://) veya [https://](https://) dışındaki herhangi bir şema ile başlarsa NotSupportedException fırlatılacaktır. 

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [HttpWebRequest](../../httpwebrequest/)
* Sınıf [String](../../../system/string/)
* Sınıf [WebRequest](../)
* Sınıf [Uri](../../../system/uri/)
* Ad alanı [System::Net](../../)
* Library [Aspose.Slides](../../../)