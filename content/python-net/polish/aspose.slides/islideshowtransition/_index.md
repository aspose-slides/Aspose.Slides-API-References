---
title: ISlideShowTransition class
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/islideshowtransition/
---
## ISlideShowTransition klasa

Reprezentuje przejście pokazu slajdów.

Typ ISlideShowTransition udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`sound`](/slides/python-net/pl/aspose.slides/islideshowtransition/sound/) | Zwraca lub ustawia osadzone dane audio.<br/>            Read-write [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/pl/aspose.slides/islideshowtransition/sound_mode/) | Ustawia lub zwraca tryb dźwięku dla przejścia slajdu.<br/>            Read-write [`TransitionSoundMode`](/slides/python-net/pl/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/pl/aspose.slides/islideshowtransition/sound_loop/) | Ten atrybut określa, czy dźwięk będzie się powtarzał aż do wystąpienia kolejnego zdarzenia dźwiękowego w<br/>            pokazu slajdów.<br/>            Read-write **bool**. |
| [`advance_on_click`](/slides/python-net/pl/aspose.slides/islideshowtransition/advance_on_click/) | Określa, czy kliknięcie myszy przejdzie do następnego slajdu, czy nie. Jeśli ten atrybut nie jest<br/>            określony, przyjmowana jest wartość true.<br/>            Read-write **bool**. |
| [`advance_after`](/slides/python-net/pl/aspose.slides/islideshowtransition/advance_after/) | Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie.<br/>            Read/write **bool**. |
| [`advance_after_time`](/slides/python-net/pl/aspose.slides/islideshowtransition/advance_after_time/) | Określa czas w milisekundach, po którym powinno rozpocząć się przejście. To ustawienie<br/>            może być używane w połączeniu z atrybutem advClick. Jeśli ten atrybut nie jest określony<br/>            przyjmowane jest założenie, że nie nastąpi automatyczne przejście.<br/>            Read-write **int**. |
| [`speed`](/slides/python-net/pl/aspose.slides/islideshowtransition/speed/) | Określa prędkość przejścia, która ma być użyta przy przechodzeniu z bieżącego slajdu<br/>            do następnego.<br/>            Read-write [`TransitionSpeed`](/slides/python-net/pl/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/pl/aspose.slides/islideshowtransition/value/) | Wartość przejścia pokazu slajdów.<br/>            Read-only [`ITransitionValueBase`](/slides/python-net/pl/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/pl/aspose.slides/islideshowtransition/type/) | Typ przejścia.<br/>            Read-write [`TransitionType`](/slides/python-net/pl/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/pl/aspose.slides/islideshowtransition/sound_is_built_in/) | Określa, czy dźwięk jest wbudowany. Jeśli ten atrybut ma wartość true, aplikacja generująca zostaje poinformowana, aby sprawdzić atrybut name określony dla tego dźwięku<br/>            na liście wbudowanych dźwięków i może wtedy wyświetlić niestandardową nazwę lub interfejs użytkownika w razie potrzeby.<br/>            Read-write **bool**. |
| [`sound_name`](/slides/python-net/pl/aspose.slides/islideshowtransition/sound_name/) | Określa nazwę dźwięku przejścia czytelną dla człowieka. Właściwość [`ISlideShowTransition.sound`](/slides/python-net/pl/aspose.slides/islideshowtransition/sound) musi być przypisana, aby uzyskać lub ustawić nazwę dźwięku.<br/>            Read-write **str**. |
| [`duration`](/slides/python-net/pl/aspose.slides/islideshowtransition/duration/) | Pobiera lub ustawia czas trwania efektu przejścia slajdu w milisekundach.<br/>            Read/write **int**. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)