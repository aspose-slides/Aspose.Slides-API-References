---
title: ReadAsync()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest asynchroon een reeks bytes van de huidige stream, verschuift de positie in de stream met het aantal gelezen bytes, en controleert annuleringsverzoeken.
type: docs
weight: 40
url: /nl/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) methode


Leest asynchroon een reeks bytes van de huidige stream, verschuift de positie in de stream met het aantal gelezen bytes, en controleert annuleringsverzoeken.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte array waarin de gelezen bytes worden geschreven. |
| offset | **int32_t** | Een op 0 gebaseerde positie in **buffer** om te beginnen met schrijven. |
| count | **int32_t** | Het aantal bytes om te lezen. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Het token om annuleringsverzoeken te controleren. |

### Retourwaarde

Een taak die de asynchrone leesbewerking vertegenwoordigt. De waarde van de TResult-parameter bevat het totale aantal bytes dat in de buffer is gelezen. De resultaatswaarde kan kleiner zijn dan het gevraagde aantal bytes als het aantal momenteel beschikbare bytes kleiner is dan het gevraagde aantal, of kan 0 (nul) zijn als het einde van de stream is bereikt.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Leest asynchroon een reeks bytes van de huidige stream, verschuift de positie in de stream met het aantal gelezen bytes, en controleert annuleringsverzoeken.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte array waarin de gelezen bytes worden geschreven. |
| offset | **int32_t** | Een op 0 gebaseerde positie in **buffer** om te beginnen met schrijven. |
| count | **int32_t** | Het aantal bytes om te lezen. |

### Retourwaarde

Een taak die de asynchrone leesbewerking vertegenwoordigt. De waarde van de TResult-parameter bevat het totale aantal bytes dat in de buffer is gelezen. De resultaatswaarde kan kleiner zijn dan het gevraagde aantal bytes als het aantal momenteel beschikbare bytes kleiner is dan het gevraagde aantal, of kan 0 (nul) zijn als het einde van de stream is bereikt.

## Zie ook

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [Stream](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)