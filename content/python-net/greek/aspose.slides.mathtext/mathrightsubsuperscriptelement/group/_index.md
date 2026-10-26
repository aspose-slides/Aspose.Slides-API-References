---
title: group method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/
weight: 80
---
## group(self) {#}
Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κλείδα αγκύλη προς τα κάτω

### Returns
Νέα περίπτωση του τύπου [`IMathGroupingCharacter`](/slides/python-net/el/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως η κλείδα αγκύλη προς τα κάτω ή άλλον

### Returns
Νέα περίπτωση του τύπου [`IMathGroupingCharacter`](/slides/python-net/el/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | Χαρακτήρας ομαδοποίησης όπως BOTTOM CURLY BRACKET (U+23DF) ή οποιοσδήποτε άλλος |
| position | [`MathTopBotPositions`](/slides/python-net/el/aspose.slides.mathtext/mathtopbotpositions) | Θέση του χαρακτήρα ομαδοποίησης |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/el/aspose.slides.mathtext/mathtopbotpositions) | Κατακόρυφη ευθυγράμμιση του χαρακτήρα ομάδας.<br/><br/>            Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη βάση γραμμής.<br/><br/>            Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, <br/><br/>            VerticalJustification of Top σημαίνει ότι το πάνω μέρος του αντικειμένου βρίσκεται στη βάση γραμμής;<br/><br/>            όταν VerticalJustification είναι ορισμένο σε Bottom, το κάτω μέρος του αντικειμένου είναι στη βάση γραμμής |

### See Also
* κλάση [`IMathGroupingCharacter`](/slides/python-net/el/aspose.slides.mathtext/imathgroupingcharacter)
* κλάση [`MathRightSubSuperscriptElement`](/slides/python-net/el/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* απαρίθμηση [`MathTopBotPositions`](/slides/python-net/el/aspose.slides.mathtext/mathtopbotpositions)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)