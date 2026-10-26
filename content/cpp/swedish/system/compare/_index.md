---
title: Compare()
second_title: Aspose.Slides för C++ API-referens
description: Jämför två värden.
type: docs
weight: 2731
url: /sv/system/compare/
---
## System::Compare(const TA&, const TB&) funktion

Jämför två värden.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TA | Typen för det första jämförelseobjektet |
| TB | Typen för det andra jämförelseobjektet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const TA& | Det första jämförelseobjektet |
| b | const TB& | Det andra jämförelseobjektet |

### Returvärde

- 1 om **a** är mindre än **b**; 0 om värdena är lika; 1 om **a** är större än **b**

## System::Compare(const TA&, const TB&) funktion

Jämför två flyttalvärden.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TA | Typen för det första jämförelseobjektet |
| TB | Typen för det andra jämförelseobjektet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const TA& | Det första jämförelseobjektet |
| b | const TB& | Det andra jämförelseobjektet |

### Returvärde

- 1 om **a** är mindre än **b**; 0 om värdena är lika; 1 om **a** är större än **b**

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)