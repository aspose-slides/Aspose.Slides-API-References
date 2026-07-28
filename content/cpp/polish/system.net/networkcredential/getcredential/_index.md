---
title: GetCredential()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Zwraca poświadczenia dla określonego URI i typu uwierzytelniania.
type: docs
weight: 92
url: /pl/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) metoda


Zwraca poświadczenia dla określonego URI i typu uwierzytelniania.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adres URI. |
| authenticationType | [String](../../../system/string/) | Typ uwierzytelniania. |

## NetworkCredential::GetCredential(String, int32_t, String) metoda


Zwraca poświadczenia dla określonej nazwy hosta, portu i typu uwierzytelniania.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nazwa hosta. |
| port | **int32_t** | Numer portu. |
| authenticationType | [String](../../../system/string/) | Typ uwierzytelniania. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [NetworkCredential](../)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)