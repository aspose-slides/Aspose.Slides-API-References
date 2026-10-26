---
title: GetHostEntry()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine neue IPHostEntry-class-Instanz mittels der angegebenen Zeichenfolge, die einen Hostnamen oder eine IP-Adresse enthält.
type: docs
weight: 79
url: /de/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) Methode

Erstellt eine neue IPHostEntry-class-Instanz mittels der angegebenen Zeichenfolge, die einen Hostnamen oder eine IP-Adresse enthält.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Eine Zeichenfolge, die einen Hostnamen oder eine IP-Adresse enthält. |

### Return Value

Eine neu erstellte IPHostEntry-class-Instanz.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) Methode

Erstellt eine neue IPHostEntry-class-Instanz mit der angegebenen IP-Adresse.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Die IP-Adresse. |

### Return Value

Eine neu erstellte IPHostEntry-class-Instanz.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPHostEntry](../../iphostentry/)
* Klasse [String](../../../system/string/)
* Klasse [Dns](../)
* Klasse [IPAddress](../../ipaddress/)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)