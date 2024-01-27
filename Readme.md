<del>
Papers for HCI Evaluation

1. Development of a Smart Home Interface With Older Adults: Multi-Method Co-Design Study
https://aging.jmir.org/2023/1/e44439/

2. An Electronic Disease Early Warning System in Sana’a Governorate, Yemen: Evaluation Study
https://publichealth.jmir.org/2019/4/e14295

3. Notes on interviews
Table 8.1 Overview of Data Gathering Techniques and Their Use @ INTERACTION DESIGN beyond human-computer interaction book
</del>

## Μέρος Β - Υλοποίηση: 40 μονάδες

### Ερώτημα 1 – Λειτουργικό υπόδειγμα υψηλής πιστότητας
Σε αυτό το μέρος θα γίνει η αρχική κατασκευή του λογισμικού για την εφαρμογή που σχεδιάσατε στην προηγούμενη ΓΕ. Ο βασικός στόχος δεν είναι η υλοποίηση της τελικής εφαρμογής, αλλά μια μελέτη διάδρασης με χρήση έτοιμων εργαλείων, βιβλιοθηκών, και κώδικα που θα βρείτε σε αποθετήρια όπως το github ή/και στα αντίστοιχα εργαλεία ανάπτυξης που θα επιλέξετε. Δεν είναι απαραίτητο να υλοποιήσετε την ίδια ακριβώς αρχική σχεδίαση. Έχετε την ευχέρεια να επιλέξετε κάτι πιο απλό. Προαιρετικά μπορείτε να κάνετε χρήση κάποιας βοηθητικής βιβλιοθήκης. Για την τεκμηρίωση μπορείτε να χρησιμοποιήσετε ενδεικτικές οθόνες ή/και βίντεο από τα εργαλεία ανάπτυξης.
[40 μονάδες]

#### Απάντηση 
Η βασική παραδοχή για το σύστημα αυτό είναι πως η εφαρμογη πρέπει να ειδοποιεί άμεσα τον κάτοχο του τηλεφώνου όταν η ποιότητα του αέρα ξεπεράσει κάποιο όριο. Χρησιμοποιήθηκε σαν παράδειγμα η εφαρμογή flutter https://github.com/Air-Quality-Index/Airometer.git η οποία έγινε εδώ forked https://github.com/std133524/Airometer-new.

Καθώς τα δεδομένα δεν ήταν εύκολο να παρθούν για όλες τις περιπτώσεις έγινε επέμβαση στο κώδικα ώστε με τυχαίο τρόπο να εμφανίζονται όλες οι κακές ή καλές ενδείξεις της ποιότητας του αέρα

Η αλλαγή στον κώδικα έγινε εδώ σαν πρόσθεση συνάρτησης Random:
https://github.com/std133524/Airometer-new/blob/18d24dba8fb42ef986cee303b80a851c5ca5d73c/lib/widgets/aqi_data_widget.dart#L19C5-L21C1

To τελικό αποτέλεσμα έπειτα από αρκετές εκτελέσεις της εφαρμογής είναι σε αυτό το animated gif:

Screen shots απο την χρήση της εφαρμογής. https://github.com/std133524/Airometer-new/blob/master/screenshots/present/
![Εφαρμογη Ποιότητας Αέρα](https://github.com/std133524/Airometer-new/blob/master/screenshots/present/annimated.png)


## Μέρος Γ – Aξιολόγηση με χρήστες: 30 μονάδες

### Ερώτημα 1 – Μεθοδολογία
Μελετήστε την τρέχουσα επιστημονική βιβλιογραφία και ετοιμάστε μια σύντομη αναφορά (300-500 λέξεων) των μεθοδολογιών που χρησιμοποιούνται για να αξιολογήσουν την λειτουργία παρόμοιων εφαρμογών με χρήστες. Ο σκοπός σε αυτό το ερώτημα είναι να γίνει κατανόηση και κριτική σε υπάρχουσες εργασίες ως θεωρητικό πλαίσιο για την αξιολόγηση που θα γίνει στο επόμενο ερώτημα. Τα άρθρα που θα διαλέξετε θα πρέπει να έχουν τουλάχιστον δύο ετεροαναφορές / έτος και να έχουν δημοσιευτεί μετά το 2010. Η αναφορά των άρθρων στο κείμενό σας θα πρέπει να γίνει με το στυλ APA και θα πρέπει να βρίσκεται στο τέλος αυτής της απάντησης. Ακόμη, η απάντηση θα πρέπει να περιλαμβάνει μια λίστα με τις πιο σημαντικές λειτουργίες και τα αντίστοιχα κριτήρια αξιολόγησης, όπως αυτά είχαν αρχικά εντοπιστεί κατά την ανάπτυξη της εφαρμογής στην προηγούμενη ΓΕ. Τέλος, θα πρέπει να παρουσιάσετε συνοπτικά (300 λέξεις) την μεθοδολογία που θα ακολουθήσετε καθώς και ενδεικτικές οθόνες-διαγράμματα, έτσι ώστε να μπορεί και κάποιος τρίτος (πέρα από εσάς) να πραγματοποιήσει ή/και να ερμηνεύσει την αξιολόγηση και τα αποτελέσματα της. Για την βελτιστοποίηση της μεθοδολογίας αξιολόγησης μπορείτε να κάνετε μερικές δοκιμές της μεθόδου-τεχνικής με έναν χρήστη πριν προχωρήσετε σε περισσότερους χρήστες. 
https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/usability-evaluation
https://www.nngroup.com/topic/research-methods/
[10 μονάδες]

#### Απάντηση

Η πρώτη δημοσίευση που βρέθηκε [Evaluation of the Usability of a Mobile Application for Public Air Quality Information Jorge-Luis Pérez-Medina 1(&) , Rasa Zalakeviciute 1,2 ,
Yves Rybarczyk 1 , and Mario González]  
https://link.springer.com/chapter/10.1007/978-3-030-20040-4_41
https://annas-archive.org/scidb/10.1007/978-3-030-20040-4_41?scidb_verified=1

αφορά πρότυπα ερωτηματολόγια ευχρηστίας. Μια περίληψη των διάφορων ερωτηματόλογίων ευχρηστίας εμφανίζονται στην παράγραφο 2.3.2 του βιβλίου "Αξιολόγηση
Διαδραστικών Συστημάτων με Επίκεντρο το Χρήστη", του Παναγιώτη Κουτσαμπάση:
https://eclass.aegean.gr/modules/document/file.php/511265/Doc1_%CE%91%CE%BE%CE%B9%CE%BF%CE%BB%CF%8C%CE%B3%CE%B7%CF%83%CE%B7%20%CE%94%CE%B9%CE%B1%CE%B4%CF%81%CE%B1%CF%83%CF%84%CE%B9%CE%BA%CF%8E%CE%BD.pdf#page=67&zoom=auto,-98,269

Στην συγκεκρινένη δημοσίευση έγινε χρήση του ερωτηματολογίου CSUQ: Computer System Usability Questionnaire https://garyperlman.com/quest/quest.cgi

Χρήση του IBM CSUQ καθώς και του https://en.wikipedia.org/wiki/Web_Content_Accessibility_Guidelines στο 2o paper

Στην δεύτερη δημοσίευση [Accessibility Evaluation of Mobile Applications for Monitoring Air Quality Patricia Acosta-Vargas 1(&) , Rasa Zalakeviciute 1 , Sergio Luján-Mora 2 , and Wilmar Hernandez  Accessibility Evaluation of Mobile Applications for Monitoring Air Quality
https://sci-hub.ru/10.1007/978-3-030-11890-7_61

γίνεται χρήστη των web standards WCAG 2.1 για αξιολόγιση παρόμοιων εφαρμογών AQI. Κυρίως εμφανίστηκαν προβλήματα στην αντίθεση εικόνας καθώς και δυσκολία στον πάτημα πλήκτρου καθώς και δυσκολία στην κατανόηση των ετικετών όπως εμφανίζονται πάνω σε διάφορες επιλογές.

Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.

### Ερώτημα 2 – Μελέτη στο πεδίο
Πραγματοποιήστε αξιολόγηση με χρήστες στο πεδίο (ενότητα 9.4 του Dix et al. και κεφάλαιο field studies στον Krum) της ευχρηστίας και της αποτελεσματικότητας (αναφορικά με τα επιμέρους κριτήρια που έχετε ορίσει στο προηγούμενο μέρος) της εφαρμογής που αναπτύξατε με πέντε τουλάχιστον χρήστες των δύο εναλλακτικών διεπαφών. Η αξιολόγηση με τους χρήστες θα πρέπει να γίνει αναφορικά με δύο τουλάχιστον συμπληρωματικές τεχνικές συλλογής δεδομένων (π.χ., προτίμηση με βάση συνέντευξη-ερωτηματολόγιο και αποτελεσματικότητα με βάση τα συμπεριφορικά δεδομένα που μαζεύτηκαν από τις συσκευές διάδρασης) και για δύο τουλάχιστον βασικές διεργασίες, όπως αυτά προκύπτουν από την αρχική ανάλυση-σχεδίαση στην προηγούμενη ΓΕ.
[10 μονάδες]

#### Απάντηση
Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.

Η αξιολόγιση θα γίνει σύμφωνα με τα standards όπως παρουσιάστηκαν στις 2 αυτές δημοσιεύσεις. 
Θα χρησιμοποιηθεί κυρίως το  IBM Computer Usability Satisfaction Questionnaires https://garyperlman.com/quest/quest.cgi
Για την εφαρμογή που έχει γίνει fork θα αποτελείται μόνο από μια οθόνη που θα ανανεώνεται συνεχώς και θα εμφανίζει μηνήματα εάν ξεπεραστεί το επιτρεπτό όριο.


### Ερώτημα 3 – Αναφορά
Ετοιμάστε αναλυτική αναφορά των αποτελεσμάτων της αξιολόγησης με χρήστες, συμπεριλαμβάνοντας πίνακες-γραφήματα-εικόνες από πολλαπλά δεδεμένα: 1) φωτογραφίες από την διάδραση με τους χρήστες, όπου φαίνεται τόσο ο χρήστης όσο και η εφαρμογή, 2) ενδεικτικές οθόνες της χρήσης της εφαρμογής με επισημάνσεις και 3) οπτικοποίηση από δεδομένα με analytics και log files. Επίσης, η αναφορά θα πρέπει να περιλαμβάνει μια ενότητα συμπερασμάτων που βασίζονται σε σύνθεση διαφορετικών δεδομένων καθώς και με προτάσεις και οθόνες για τον ανασχεδιασμό της εφαρμογής, που θα τεκμηριώνεται από τα δεδομένα της αξιολόγησης με τους χρήστες. https://www.nngroup.com/articles/actionable-usability-findings/
https://www.usability.gov/how-to-and-tools/resources/templates/report-template-usability-test.html
[10 μονάδες]

#### Απάντηση
Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.


## Μέρος Δ - Παρουσίαση προόδου: 10 μονάδες (μπόνους)
Να ετοιμάσετε παρουσίαση πέντε λεπτών (περίπου 5 διαφάνειες) με έμφαση στην λειτουργική εφαρμογή και στην μέθοδο της αξιολόγησης με χρήστες, καθώς και στα πρώτα αποτελέσματα από έναν ή περισσότερους χρήστες. Η παρουσίαση θα πραγματοποιηθεί κατά τη διάρκεια της ΟΣΣ3. 
[10 μονάδες]

#### Απάντηση
Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.
