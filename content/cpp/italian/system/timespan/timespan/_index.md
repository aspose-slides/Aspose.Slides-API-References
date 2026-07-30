---
title: TimeSpan()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisce un oggetto TimeSpan che rappresenta un intervallo di tempo pari a zero.
type: docs
weight: 1
url: /it/system/timespan/timespan/
---
## TimeSpan::TimeSpan() costruttore

Costruisce un oggetto [TimeSpan](../) che rappresenta un intervallo di tempo pari a zero.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) costruttore

Costruisce un'istanza della classe [TimeSpan](../) che rappresenta l'intervallo di tempo specificato.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ticks | **int64_t** | L'intervallo di tempo da rappresentare dall'istanza in costruzione espresso come numero di intervalli di 100 nanosecondi. |

## TimeSpan::TimeSpan(int, int, int) costruttore

Costruisce un'istanza della classe [TimeSpan](../) che rappresenta l'intervallo di tempo pari alla somma del numero specificato di ore, minuti e secondi.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hours | int | Il numero di ore nella componente ore dell'intervallo di tempo da rappresentare dall'istanza in costruzione |
| minutes | int | Il numero di minuti nella componente minuti dell'intervallo di tempo da rappresentare dall'istanza in costruzione |
| seconds | int | Il numero di secondi nella componente secondi dell'intervallo di tempo da rappresentare dall'istanza in costruzione |

## TimeSpan::TimeSpan(int, int, int, int, int) costruttore

Costruisce un'istanza della classe [TimeSpan](../) che rappresenta l'intervallo di tempo pari alla somma del numero specificato di ore, minuti, secondi e millisecondi.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| days | int | Il numero di giorni nella componente giorni dell'intervallo di tempo da rappresentare dall'istanza in costruzione |
| hours | int | Il numero di ore nella componente ore dell'intervallo di tempo da rappresentare dall'istanza in costruzione |
| minutes | int | Il numero di minuti nella componente minuti dell'intervallo di tempo da rappresentare dall'istanza in costruzione |
| seconds | int | Il numero di secondi nella componente secondi dell'intervallo di tempo da rappresentare dall'istanza in costruzione |
| milliseconds | int | Il numero di millisecondi nella componente millisecondi dell'intervallo di tempo da rappresentare dall'istanza in costruzione |

## TimeSpan::TimeSpan(const TimeSpan\&) costruttore

Costruisce un oggetto [TimeSpan](../) che rappresenta l'intervallo di tempo pari all'intervallo di tempo rappresentato dall'oggetto [TimeSpan](../) specificato.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Vedi anche

* Classe [TimeSpan](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)