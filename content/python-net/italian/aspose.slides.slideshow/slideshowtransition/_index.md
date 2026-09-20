---
title: SlideShowTransition class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition classe

Rappresenta la transizione dello slideshow.

Il tipo SlideShowTransition espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`sound`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/sound/) | Restituisce o imposta i dati audio incorporati.<br/>            Lettura/scrittura [`IAudio`](/slides/python-net/it/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/sound_mode/) | Imposta o restituisce la modalità sonora per la transizione della diapositiva.<br/>            Lettura/scrittura [`TransitionSoundMode`](/slides/python-net/it/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/sound_loop/) | Questo attributo specifica se il suono verrà ripetuto fino a quando non si verifica il successivo evento sonoro nella<br/>            presentazione.<br/>            Lettura/scrittura **bool**. |
| [`advance_on_click`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | Specifica se un clic del mouse avanzerà la diapositiva o meno. Se questo attributo non è<br/>            specificato, si assume un valore true.<br/>            Lettura/scrittura **bool**. |
| [`advance_after`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/advance_after/) | Questo attributo specifica se la presentazione si sposterà alla diapositiva successiva dopo un certo intervallo di tempo.<br/>            Lettura/scrittura **bool**. |
| [`advance_after_time`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | Specifica il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. Questa impostazione<br/>            può essere usata in combinazione con l'attributo advClick. Se questo attributo non è specificato<br/>            si assume che non avverrà alcun avanzamento automatico.<br/>            Lettura/scrittura **int**. |
| [`speed`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/speed/) | Specifica la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente<br/>            a quella successiva.<br/>            Lettura/scrittura [`TransitionSpeed`](/slides/python-net/it/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/value/) | Valore della transizione della presentazione.<br/>            Solo lettura [`ITransitionValueBase`](/slides/python-net/it/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/type/) | Tipo di transizione.<br/>            Lettura/scrittura [`TransitionType`](/slides/python-net/it/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | Specifica se questo suono è un suono incorporato o meno. Se questo attributo è impostato su true, allora<br/>            l'applicazione generatrice viene avvisata di controllare l'attributo name specificato per questo suono<br/>            nella sua lista di suoni incorporati e può quindi presentare un nome personalizzato o un'interfaccia utente secondo necessità.<br/>            Lettura-scrittura **bool**. |
| [`sound_name`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/sound_name/) | Specifica un nome leggibile dall'uomo per il suono della transizione. La proprietà [`SlideShowTransition.sound`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/sound) deve essere assegnata per ottenere o impostare il nome del suono.<br/>            Lettura-scrittura **str**. |
| [`duration`](/slides/python-net/it/aspose.slides.slideshow/slideshowtransition/duration/) | Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi.<br/>            Lettura/scrittura **int**. |


### Vedi anche
* modulo [`aspose.slides.slideshow`](/slides/python-net/it/aspose.slides.slideshow)
* libreria [`Aspose.Slides`](/slides/python-net)