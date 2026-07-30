---
title: BeginGetHostEntry()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Spouští asynchronní operaci pro vytvoření nové instance třídy IPHostEntry-class pomocí zadaného řetězce, který obsahuje název hostitele nebo IP adresu.
type: docs
weight: 105
url: /cs/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) metoda

Spouští asynchronní operaci pro vytvoření nové instance třídy IPHostEntry pomocí zadaného řetězce, který obsahuje název hostitele nebo IP adresu.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Řetězec, který obsahuje název hostitele nebo IP adresu. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které se zavolá po dokončení operace. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jednoznačnému identifikování každé asynchronní operace. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) metoda

Spouští asynchronní operaci pro vytvoření nové instance třídy IPHostEntry pomocí zadané IP adresy.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP adresa. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které se zavolá po dokončení operace. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jednoznačnému identifikování každé asynchronní operace. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [String](../../../system/string/)
* Třída [Object](../../../system/object/)
* Třída [Dns](../)
* Třída [IPAddress](../../ipaddress/)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)