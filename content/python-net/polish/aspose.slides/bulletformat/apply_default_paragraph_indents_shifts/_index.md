---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides dla Pythona poprzez .NET API
description: 
type: docs
url: /pl/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Ustawia domyślne niezerowe przesunięcia dla efektywnego paragrafu Indent i MarginLeft, gdy włączone są wypunktowania (tak jak PowerPoint robi, jeśli włączone są wypunktowania/numery w paragrafie). Jeśli wypunktowania są wyłączone, po prostu resetuje Indent i MarginLeft (tak jak PowerPoint robi, jeśli wyłączone są wypunktowania/numery w paragrafie). Przesunięcia wcięć są stosowane w odniesieniu do bieżącego kontekstu wypunktowania – IBulletFormat.Type, .NumberedBulletStyle i FontHeight pierwszej części. Niezerowe przesunięcia wcięć są stosowane do efektywnego Indent i MarginLeft bieżącego paragrafu (sprawiając, że wartości wynikowe są wartościami lokalnymi).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wywołanie tej metody nie ma znaczenia i rzuca **System.InvalidOperationException** w następujących przypadkach:<br/>            jeśli obiekt formatowany nadrzędny nie jest paragrafem (na przykład wywołanie ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() spowoduje wyjątek);<br/>            lub jeśli paragraf nie został dodany do żadnej kolekcji ITextFrame.Paragraphs (dodaj go najpierw); |



### Zobacz także
* klasa [`BulletFormat`](/slides/python-net/pl/aspose.slides/bulletformat)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)