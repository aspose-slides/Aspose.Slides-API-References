---
title: LoadOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/loadoptions/
---
## LoadOptions κλάση

Επιτρέπει τον προσδιορισμό πρόσθετων επιλογών (όπως μορφή ή προεπιλεγμένη γραμματοσειρά) κατά τη φόρτωση μιας παρουσίασης.

Ο τύπος LoadOptions εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides/loadoptions/__init__/#) | Creates new default load options. |
| [`__init__(self, load_format)`](/slides/python-net/el/aspose.slides/loadoptions/__init__/#loadformat) | Creates new load options. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`load_format`](/slides/python-net/el/aspose.slides/loadoptions/load_format/) | Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση.<br/>            Ανάγνωση/Εγγραφή [`LoadFormat`](/slides/python-net/el/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/el/aspose.slides/loadoptions/default_regular_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται εάν η πηγή γραμματοσειράς δεν βρεθεί.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`default_symbol_font`](/slides/python-net/el/aspose.slides/loadoptions/default_symbol_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται εάν η πηγή γραμματοσειράς δεν βρεθεί.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`default_asian_font`](/slides/python-net/el/aspose.slides/loadoptions/default_asian_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά Asian που χρησιμοποιείται εάν η πηγή γραμματοσειράς δεν βρεθεί.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`password`](/slides/python-net/el/aspose.slides/loadoptions/password/) | Ανακτά ή ορίζει τον κωδικό πρόσβασης.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`only_load_document_properties`](/slides/python-net/el/aspose.slides/loadoptions/only_load_document_properties/) | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό.<br/>            Η τιμή true σημαίνει ότι πρέπει να φορτωθούν μόνο οι ιδιότητες του εγγράφου από ένα κρυπτογραφημένο <br/>            αρχείο παρουσίασης και ο κωδικός πρέπει να αγνοηθεί.<br/>            Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση πρέπει να φορτωθεί με χρήση του σωστού <br/>            κωδικού.<br/>            Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, τότε η τιμή της ιδιότητας παραλείπεται πάντα.<br/>            Εάν οι ιδιότητες του εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true, τότε<br/>            οι ιδιότητες του εγγράφου δεν μπορούν να φορτωθούν και θα προκληθεί εξαίρεση.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`warning_callback`](/slides/python-net/el/aspose.slides/loadoptions/warning_callback/) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης <br/>            θα συνεχιστεί ή θα διακοπεί.<br/>            Ανάγνωση/Εγγραφή [`IWarningCallback`](/slides/python-net/el/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/el/aspose.slides/loadoptions/blob_management_options/) | Αναπαριστά τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς χειρισμού Binary Large Objects (BLOBs),<br/>            όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOBs στη μνήμη. Αυτές οι επιλογές προορίζονται να ρυθμίσουν<br/>            το καλύτερο λόγο απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις.<br/>            Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μία ενιαία οντότητα - δηλαδή το BLOB μπορεί <br/>            να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. |
| [`document_level_font_sources`](/slides/python-net/el/aspose.slides/loadoptions/document_level_font_sources/) | Καθορίζει τις πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση.<br/>            Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις |
| [`interruption_token`](/slides/python-net/el/aspose.slides/loadoptions/interruption_token/) | Το διακριτικό για παρακολούθηση αιτημάτων διακοπής.<br/>            <br/>            Αυτό το διακριτικό διαχειρίζεται ολόκληρη τη διάρκεια ζωής της εμφάνισης [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). Οποιαδήποτε μακρά λειτουργία, όπως η φόρτωση <br/>            ή η αποθήκευση της παρουσίασης, θα διακοπεί με την κλήση της μεθόδου [`InterruptionTokenSource.interrupt`](/slides/python-net/el/aspose.slides/interruptiontokensource/interrupt) του <br/>            [`InterruptionTokenSource`](/slides/python-net/el/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/el/aspose.slides/loadoptions/resource_loading_callback/) | Επιστρέφει ή ορίζει τη διεπαφή callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων.<br/>            Ανάγνωση/Εγγραφή [`IResourceLoadingCallback`](/slides/python-net/el/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/el/aspose.slides/loadoptions/spreadsheet_options/) | Ανακτά τις επιλογές για τα λογιστικά φύλλα. Για παράδειγμα, αυτές οι επιλογές επηρεάζουν τον υπολογισμό τύπων για διαγράμματα. |
| [`default_text_language`](/slides/python-net/el/aspose.slides/loadoptions/default_text_language/) | Επιστρέφει ή ορίζει την προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης.<br/>             Ανάγνωση/Εγγραφή **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/el/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Καθορίζει αν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.<br/>            <br/>Οι τύποι των ενσωματωμένων δυαδικών αντικειμένων:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/el/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/el/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Ανάγνωση/Εγγραφή **bool**. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)