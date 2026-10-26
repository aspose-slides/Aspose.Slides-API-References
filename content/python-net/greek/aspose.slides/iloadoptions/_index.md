---
title: ILoadOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/iloadoptions/
---
## ILoadOptions κλάση

Επιτρέπει να καθορίσετε πρόσθετες επιλογές (όπως μορφή ή προεπιλεγμένη γραμματοσειρά) κατά τη φόρτωση μιας παρουσίασης.

Ο τύπος ILoadOptions εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`load_format`](/slides/python-net/el/aspose.slides/iloadoptions/load_format/) | Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση.<br/>            Ανάγνωση/Εγγραφή [`LoadFormat`](/slides/python-net/el/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/el/aspose.slides/iloadoptions/default_regular_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται όταν η πηγή γραμματοσειράς δεν βρεθεί.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`default_symbol_font`](/slides/python-net/el/aspose.slides/iloadoptions/default_symbol_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται όταν η πηγή γραμματοσειράς δεν βρεθεί.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`default_asian_font`](/slides/python-net/el/aspose.slides/iloadoptions/default_asian_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά Asian που χρησιμοποιείται όταν η πηγή γραμματοσειράς δεν βρεθεί.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`password`](/slides/python-net/el/aspose.slides/iloadoptions/password/) | Επιστρέφει ή ορίζει τον κωδικό πρόσβασης.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`only_load_document_properties`](/slides/python-net/el/aspose.slides/iloadoptions/only_load_document_properties/) | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό.<br/>            Η τιμή true σημαίνει ότι μόνο οι ιδιότητες του εγγράφου πρέπει να φορτωθούν από ένα κρυπτογραφημένο <br/>            αρχείο παρουσίασης και ο κωδικός πρέπει να αγνοηθεί.<br/>            Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση πρέπει να φορτωθεί με χρήση του σωστού <br/>            κωδικού.<br/>            Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, τότε η τιμή της ιδιότητας αγνοείται πάντα.<br/>            Εάν οι ιδιότητες του εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true, τότε<br/>            οι ιδιότητες του εγγράφου δεν μπορούν να φορτωθούν και θα εκτοξευθεί εξαίρεση.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`warning_callback`](/slides/python-net/el/aspose.slides/iloadoptions/warning_callback/) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης <br/>            θα συνεχιστεί ή θα ακυρωθεί.<br/>            Ανάγνωση/Εγγραφή [`IWarningCallback`](/slides/python-net/el/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/el/aspose.slides/iloadoptions/blob_management_options/) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς των Binary Large Objects (BLOBs),<br/>            όπως η χρήση προσωρινών αρχείων ή το μέγιστο μέγεθος BLOBs σε μνήμη. Αυτές οι επιλογές προορίζονται να ρυθμίσουν<br/>            την καλύτερη αναλογία απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις.<br/>            Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μία ενιαία οντότητα - δηλαδή το BLOB μπορεί <br/>            να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. |
| [`document_level_font_sources`](/slides/python-net/el/aspose.slides/iloadoptions/document_level_font_sources/) | Καθορίζει τις πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση.<br/>            Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις |
| [`interruption_token`](/slides/python-net/el/aspose.slides/iloadoptions/interruption_token/) | Το διακριτικό για την παρακολούθηση αιτήσεων διακοπής.<br/>            <br/>            Αυτό το διακριτικό διαχειρίζεται όλη τη διάρκεια ζωής του αντικειμένου [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). Οποιαδήποτε μακρά λειτουργία, όπως η φόρτωση ή η αποθήκευση παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου [`IInterruptionTokenSource.interrupt`](/slides/python-net/el/aspose.slides/iinterruptiontokensource/interrupt) του <br/>            [`IInterruptionTokenSource`](/slides/python-net/el/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/el/aspose.slides/iloadoptions/resource_loading_callback/) | Επιστρέφει ή ορίζει τη διεπαφή callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων.<br/>            Ανάγνωση/Εγγραφή [`IResourceLoadingCallback`](/slides/python-net/el/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/el/aspose.slides/iloadoptions/spreadsheet_options/) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό επιπλέον συμπεριφοράς λογιστικών φύλλων. |
| [`default_text_language`](/slides/python-net/el/aspose.slides/iloadoptions/default_text_language/) | Επιστρέφει ή ορίζει την προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης.<br/>             Ανάγνωση/Εγγραφή **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/el/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.<br/>            <br/>Οι τύποι των ενσωματωμένων δυαδικών αντικειμένων:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/el/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/el/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Ανάγνωση/Εγγραφή **bool**. |

### Δες επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)