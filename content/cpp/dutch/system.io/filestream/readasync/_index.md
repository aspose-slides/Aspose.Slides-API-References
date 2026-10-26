---
title: ReadAsync()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest asynchroon een reeks bytes van de huidige stream, verschuift de positie in de stream met het aantal gelezen bytes en bewaakt annuleringverzoeken.
type: docs
weight: 196
url: /nl/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method


Leest asynchroon een reeks bytes van de huidige stream, verschuift de positie in de stream met het aantal gelezen bytes en houdt annulering-verzoeken in de gaten.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array waarin de gelezen bytes worden weggeschreven. |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven. |
| count | **int32_t** | Het aantal bytes om te lezen. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Het token om annulering-verzoeken te monitoren. |

### Retourwaarde

Een taak die de asynchrone leesbewerking vertegenwoordigt. De waarde van de TResult-parameter bevat het totale aantal bytes dat in de buffer is gelezen. De resultaatwaarde kan kleiner zijn dan het aangevraagde aantal bytes als het momenteel beschikbare aantal bytes kleiner is dan het aangevraagde aantal, of kan 0 (nul) zijn als het einde van de stream is bereikt.

## Zie ook

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)