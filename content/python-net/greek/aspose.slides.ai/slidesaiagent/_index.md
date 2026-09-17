---
title: SlidesAIAgent class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent κλάση

Παρέχει λειτουργίες με τεχνητή νοημοσύνη για την επεξεργασία παρουσιάσεων.

Ο τύπος SlidesAIAgent εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/el/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Αρχικοποιεί ένα νέο στιγμιότυπο του [`SlidesAIAgent`](/slides/python-net/el/aspose.slides.ai/slidesaiagent) με έναν προσαρμοσμένο πελάτη AI.<br/>Χρησιμοποιήστε αυτήν τη υπερφόρτωση για να καθορίσετε τον πάροχο AI, να παρέχετε το δικό σας LLM ή να προσαρμόσετε τη<br/>σύνδεση (για παράδειγμα, παρέχοντας το δικό σας `HttpClient`).<br/>Μπορεί να χρησιμοποιηθεί οποιαδήποτε υλοποίηση του [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient), συμπεριλαμβανομένων:<br/><br/>* [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>Για τη χρήση του ενσωματωμένου [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient) με την προεπιλεγμένη διαμόρφωση,<br/>χρησιμοποιήστε την υπερφόρτωση **SlidesAIAgent.#ctor** αντί αυτού. |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.ai/slidesaiagent/__init__/#) | Αρχικοποιεί ένα νέο στιγμιότυπο του [`SlidesAIAgent`](/slides/python-net/el/aspose.slides.ai/slidesaiagent) χρησιμοποιώντας το ενσωματωμένο<br/>[`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient) με την προεπιλεγμένη διαμόρφωσή του. Ο πελάτης συνδέεται με<br/>το δικό του LLM της Aspose και δεν απαιτεί πρόσθετη διαμόρφωση.<br/>Για τη χρήση διαφορετικού πελάτη AI, χρησιμοποιήστε την υπερφόρτωση **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** αντί αυτού. |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/el/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Δημιουργεί ένα στιγμιότυπο παρουσίασης από μια περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, αποφθέγματα ή αποσπάσματα κειμένου στη ζητούμενη γλώσσα. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/el/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Δημιουργεί ένα στιγμιότυπο παρουσίασης από μια περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, αποφθέγματα ή αποσπάσματα κειμένου στη ζητούμενη γλώσσα. |
| [`translate(self, presentation, language)`](/slides/python-net/el/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Μεταφράζει μια παρουσίαση στην καθορισμένη γλώσσα χρησιμοποιώντας AI (συγχρονική έκδοση). |

### Δείτε επίσης
* κλάση [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)
* κλάση [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient)
* κλάση [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)
* κλάση [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)
* κλάση [`SlidesAIAgent`](/slides/python-net/el/aspose.slides.ai/slidesaiagent)
* μονάδα [`aspose.slides.ai`](/slides/python-net/el/aspose.slides.ai)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)