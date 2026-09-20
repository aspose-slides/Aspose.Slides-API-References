---
title: ISlideShowTransition class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/islideshowtransition/
---
## ISlideShowTransition classe

Rappresenta la transizione della presentazione.

Il tipo ISlideShowTransition espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`sound`](/slides/python-net/it/aspose.slides/islideshowtransition/sound/) | Restituisce o imposta i dati audio incorporati.<br/>            Lettura-scrittura [`IAudio`](/slides/python-net/it/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/it/aspose.slides/islideshowtransition/sound_mode/) | Imposta o restituisce la modalità audio per la transizione della diapositiva.<br/>            Lettura-scrittura [`TransitionSoundMode`](/slides/python-net/it/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/it/aspose.slides/islideshowtransition/sound_loop/) | Questo attributo specifica se il suono verrà ripetuto fino al verificarsi del prossimo evento sonoro nella<br/>            presentazione.<br/>            Lettura-scrittura **bool**. |
| [`advance_on_click`](/slides/python-net/it/aspose.slides/islideshowtransition/advance_on_click/) | Specifica se un clic del mouse avanzerà la diapositiva o meno. Se questo attributo non è<br/>            specificato, viene assunto il valore true.<br/>            Lettura-scrittura **bool**. |
| [`advance_after`](/slides/python-net/it/aspose.slides/islideshowtransition/advance_after/) | Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un certo intervallo di tempo.<br/>            Lettura/scrittura **bool**. |
| [`advance_after_time`](/slides/python-net/it/aspose.slides/islideshowtransition/advance_after_time/) | Specifica il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. Questa impostazione<br/>            può essere usata in combinazione con l'attributo advClick. Se questo attributo non è specificato<br/>            si assume che non avverrà alcun avanzamento automatico.<br/>            Lettura-scrittura **int**. |
| [`speed`](/slides/python-net/it/aspose.slides/islideshowtransition/speed/) | Specifica la velocità di transizione da usare quando si passa dalla diapositiva corrente<br/>            a quella successiva.<br/>            Lettura-scrittura [`TransitionSpeed`](/slides/python-net/it/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/it/aspose.slides/islideshowtransition/value/) | Valore della transizione della presentazione.<br/>            Sola lettura [`ITransitionValueBase`](/slides/python-net/it/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/it/aspose.slides/islideshowtransition/type/) | Tipo di transizione.<br/>            Lettura-scrittura [`TransitionType`](/slides/python-net/it/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/it/aspose.slides/islideshowtransition/sound_is_built_in/) | Specifica se questo suono è integrato o meno. Se questo attributo è impostato su true, l'applicazione generatrice viene avvisata di controllare l'attributo name specificato per questo suono<br/>            nella sua lista di suoni integrati e può così fornire un nome personalizzato o un'interfaccia utente secondo necessità.<br/>            Lettura-scrittura **bool**. |
| [`sound_name`](/slides/python-net/it/aspose.slides/islideshowtransition/sound_name/) | Specifica un nome leggibile dall'uomo per il suono della transizione. La proprietà [`ISlideShowTransition.sound`](/slides/python-net/it/aspose.slides/islideshowtransition/sound) deve essere assegnata per ottenere o impostare il nome del suono.<br/>            Lettura-scrittura **str**. |
| [`duration`](/slides/python-net/it/aspose.slides/islideshowtransition/duration/) | Restituisce o imposta la durata dell'effetto di transizione della diapositiva in millisecondi.<br/>            Lettura/scrittura **int**. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)