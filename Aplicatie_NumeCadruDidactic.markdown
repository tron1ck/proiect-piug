# Aplicație: To Do List for Students

## Introducere
Această aplicație web, intitulată "To Do List for Students", a fost dezvoltată pentru a ajuta studenții să își organizeze sarcinile școlare. Aplicația respectă principiile de proiectare a interfețelor utilizator studiate la cursul PIUG și îndeplinește cerințele specificate în laboratoarele 1-4. Documentul prezintă caracteristicile UI/UX implementate, conform listei din `suport proiect piug (1).docx`, și detaliază respectarea cerințelor din `Continut si cerinte - Laboratoare PIUG.pdf`.

## Caracteristici UI/UX Implementate

### 1. Volumul interogărilor, dialogul cu utilizatorul, vocabularul tehnic (c2)
Aplicația utilizează un dialog simplu și clar cu utilizatorul, adaptat studenților. Formularele sunt intuitive, cu mesaje de eroare descriptive (e.g., "Numele trebuie să aibă cel puțin 3 caractere"). Vocabularul este non-tehnic, folosind termeni familiari precum "Adaugă Sarcină", "Listă Sarcini", "Setări". Volumul interogărilor este minim, cerând doar informațiile necesare (e.g., nume sarcină, dată, prioritate).

**Exemplu**: Mesajele de eroare de pe pagina "Adaugă Sarcină" ghidează utilizatorul fără termeni tehnici.

*(Includeți o captură de ecran a paginii "Adaugă Sarcină" cu un mesaj de eroare vizibil, e.g., după introducerea unui nume de sarcină sub 3 caractere.)*

### 2. Proiectarea pentru estetică vizuală: stimuli vizuali, codificarea informației, categorii distincte (c2)
Aplicația adoptă un design inspirat de Notion, cu stimuli vizuali clari: font modern (Inter), culori soft (gri deschis `#f5f5f5`, albastru `#3b82f6`), și iconițe (Font Awesome). Informația este codificată prin tabele (e.g., "Listă Sarcini") și culori (e.g., roșu pentru erori). Categoriile sunt distincte: "Sarcini Terminate" este separat de sarcinile active, cu stiluri vizuale diferite (text tăiat pentru sarcinile completate).

**Exemplu**: Tabelul din "Listă Sarcini" folosește culori și iconițe pentru a diferenția starea sarcinilor.

*(Includeți o captură de ecran a paginii "Listă Sarcini" care arată sarcinile active și completate.)*

### 3. Structuri mari: tipul de structură, editarea, personalizarea, layout (c2)
Aplicația folosește o structură ierarhică clară, cu 5 pagini distincte (Autentificare, Acasă, Adaugă Sarcină, Listă Sarcini, Setări). Utilizatorii pot edita sarcinile (marcare ca finalizate, ștergere) și personaliza aplicația (culori fundal și text pe pagina "Setări"). Layout-ul este centrat, cu containere albe, margini rotunjite și umbre subtile, oferind o structură organizată.

**Exemplu**: Personalizarea culorilor pe pagina "Setări" permite utilizatorilor să modifice aspectul aplicației.

*(Includeți o captură de ecran a paginii "Setări" cu previzualizarea culorilor.)*

### 4. Principiile de prezentare: echilibru, aliniere, proporție (c2)
Designul respectă echilibrul prin centrarea conținutului (`.container { max-width: 900px; margin: 0 auto; }`). Alinierea este uniformă, cu formulare și tabele aliniate central sau la stânga (e.g., tabelul din "Listă Sarcini"). Proporțiile sunt armonioase: butoanele și input-urile au dimensiuni consistente, iar spațierea este uniformă (`.task-form { gap: 10px; }`).

**Exemplu**: Formularul din "Adaugă Sarcină" are elemente aliniate și proporționate.

*(Includeți o captură de ecran a paginii "Adaugă Sarcină" care arată alinierea formularului.)*

### 5. Reguli generale de proiectarea a interfețelor (c3/slide 28)
Aplicația respectă regulile generale:  
- **Claritate**: Text clar și iconițe intuitive (e.g., coș de gunoi pentru ștergere).  
- **Consistență**: Stiluri uniforme (e.g., butoane albastre peste tot).  
- **Feedback**: Mesaje de eroare și previzualizări în timp real (e.g., în "Setări").  
- **Simplitate**: Interfață minimalistă, fără elemente inutile.

**Exemplu**: Feedback-ul imediat la selectarea culorilor pe pagina "Setări".

*(Reutilizați captura de ecran a paginii "Setări".)*

### 6. Principii de prezentare a informației pe ecran (c3/slide 36-43)
- **Organizare**: Informația este grupată logic (e.g., sarcinile active și completate sunt separate).  
- **Contrast**: Culori contrastante pentru text (`#2f3437`) și fundal (`#f5f5f5`).  
- **Spațiere**: Spațiere uniformă între elemente (`.container { padding: 25px; }`).  
- **Ierarhie vizuală**: Titluri (`h2`) și subtitluri pentru claritate.

**Exemplu**: Tabelul din "Listă Sarcini" organizează informația clar, cu ierarhie vizuală.

*(Reutilizați captura de ecran a paginii "Listă Sarcini".)*

### 7. Principii ale proiectării IU (c4/slide 4-43)
Aplicația aplică principiile IU:  
- **Accesibilitate**: Font lizibil (Inter), contrast bun.  
- **Interactivitate**: Butoane și input-uri interactive (e.g., previzualizare culori în timp real).  
- **Eficiență**: Funcții precum sortare și filtrare (e.g., "Sortează după prioritate").  
- **Personalizare**: Utilizatorii pot schimba culorile.

**Exemplu**: Filtrarea sarcinilor neterminate pe pagina "Listă Sarcini".

*(Reutilizați captura de ecran a paginii "Listă Sarcini".)*

### 8. Justificarea alegerii culorilor cu selecția din schemele armonice (c5/pg. 9-10, 11)
Culorile au fost alese pe baza unei scheme armonice monocromatice și complementare:  
- **Gri deschis (`#f5f5f5`)**: Fundal neutru, calm, inspirat de Notion.  
- **Albastru (`#3b82f6`)**: Culoare complementară pentru butoane, asociată cu încrederea.  
- **Gri închis (`#2f3437`)**: Text lizibil, contrast bun.  
Aceste culori respectă recomandările pentru aplicații educaționale, fiind relaxante și profesionale.

**Referință**: Schemele de culori au fost validate folosind [Adobe Color Wheel](https://color.adobe.com/create).

*(Includeți o captură de ecran din Adobe Color Wheel cu schema monocromatică bazată pe `#f5f5f5` și complementară cu `#3b82f6`.)*

### 9. Pentru apps: tranziții, responsivness (c7-8)
- **Tranziții**: Tranziții fluide pentru schimbarea culorilor (`body { transition: background-color 0.3s, color 0.3s; }`).  
- **Responsivitate**: Design adaptabil pentru mobil, cu un sidebar care se ascunde și un buton hamburger pentru navigare pe ecrane mici (`@media (max-width: 767px)`).

**Exemplu**: Sidebar-ul se transformă într-un meniu hamburger pe mobil.

*(Includeți două capturi de ecran: una pe desktop cu sidebar-ul vizibil și una pe mobil cu butonul hamburger.)*

### 10. Elemente de credibilitate asociate (c9/slide 9)
- **Autentificare**: Necesită conectare (username: "student", password: "pass123"), oferind un sentiment de securitate.  
- **Design profesional**: Aspect modern, inspirat de Notion, cu fonturi și culori consistente.  
- **Feedback clar**: Mesaje de eroare și starea sarcinilor sporesc încrederea utilizatorului.

**Exemplu**: Pagina de autentificare adaugă credibilitate.

*(Includeți o captură de ecran a paginii "Autentificare".)*

### 11. Elemente de uzabilitate (c9/slide 20)
- **Navigare ușoară**: Sidebar-ul cu link-uri clare (e.g., "Acasă", "Adaugă Sarcină").  
- **Feedback imediat**: Previzualizare în timp real a culorilor, mesaje de eroare.  
- **Flexibilitate**: Sortare și filtrare sarcinilor.  
- **Consistență**: Design uniform pe toate paginile.

**Exemplu**: Filtrarea sarcinilor neterminate și previzualizarea culorilor.

*(Reutilizați capturile de ecran pentru "Listă Sarcini" și "Setări".)*

### 12. Tipul testului folosit în aprecierea uzabilității (c11)
Urmează să fie realizat un test de uzabilitate în Laboratorul 5, utilizând un chestionar Google Forms cu minim 20 de întrebări, completat de un coleg. Testul va evalua navigarea, estetica, funcționalitatea și personalizarea.

**Notă**: Detaliile vor fi incluse în documentul `Testare_NumeCadruDidactic.docx`.

### 13. Evaluarea euristică a aplicației (c12)
Aplicația respectă cele 10 principii euristice ale lui Nielsen:  
- **Vizibilitatea stării sistemului**: Mesaje de eroare și starea sarcinilor (checkbox-uri).  
- **Compatibilitate cu lumea reală**: Termeni familiari (e.g., "Adaugă Sarcină").  
- **Controlul utilizatorului**: Anulare sarcină completată, ștergere totală.  
- **Consistență**: Design uniform.  
- **Prevenirea erorilor**: Validări input (e.g., prioritate între 1 și 5).  
- **Recunoaștere, nu memorare**: Placeholder-e clare (e.g., "Nume sarcină (min 3 caractere)").  
- **Flexibilitate**: Sortare, filtrare, personalizare.  
- **Design minimalist**: Interfață curată, fără elemente inutile.  
- **Recuperare din erori**: Mesaje descriptive (e.g., "Data trebuie să fie astăzi sau în viitor").  
- **Ajutor**: Introducere pe pagina "Acasă".

**Exemplu**: Mesajele de eroare și design-ul minimalist.

*(Reutilizați capturile de ecran pentru "Adaugă Sarcină" și "Acasă".)*

### 14. Elemente de joc serios (dacă este cazul) (c13)
Nu se aplică, deoarece aplicația nu include elemente de joc serios.

### 15. Aplicarea IA în proiectarea UI/UX (c14)
Aplicația a fost dezvoltată cu ajutorul Grok, un instrument AI creat de xAI. Grok a asistat în:  
- Generarea design-ului inspirat de Notion.  
- Implementarea funcționalităților (e.g., autentificare, personalizare culori).  
- Optimizarea codului pentru responsivitate și tranziții.  
- Aplicarea principiilor UI/UX conform cerințelor.

**Exemplu**: Design-ul și funcționalitățile au fost sugerate și rafinate de Grok.

## Cerințe Specifice Laboratoare PIUG

### Minim 4 pagini distincte
Aplicația conține 5 pagini: Autentificare, Acasă, Adaugă Sarcină, Listă Sarcini, Setări.

**Exemplu**: Fiecare pagină este un container distinct (e.g., `<div class="container" id="home">`).

*(Includeți capturi de ecran pentru toate cele 5 pagini.)*

### Minim 3 validări de casete de text
- **Nume sarcină**: Minim 3 caractere (`function validateTaskName(name) { return name.length >= 3; }`).  
- **Dată**: Trebuie să fie astăzi sau în viitor (`function validateDate(date) { ... }`).  
- **Prioritate**: Între 1 și 5 (`function validatePriority(priority) { ... }`).

**Exemplu**: Mesajele de eroare apar la validare pe pagina "Adaugă Sarcină".

*(Reutilizați captura de ecran pentru "Adaugă Sarcină" cu erori.)*

### Contorizare accesare controale
Navigarea folosește `clickCounts` pentru a contoriza accesările paginilor, rearanjând link-urile din sidebar. "Acasă" și "Deconectare" sunt fixe, iar celelalte se reordonează (`function updateNavOrder()`).

**Exemplu**: Link-urile se reordonează după accesare frecventă.

*(Includeți o captură de ecran a sidebar-ului după accesarea repetată a unei pagini, e.g., "Listă Sarcini".)*

### Personalizarea fundalului și a textului
Pagina "Setări" permite personalizarea culorilor fundalului și textului, cu previzualizare în timp real și salvare în `localStorage`.

**Exemplu**: Utilizatorii pot schimba culorile și le pot aplica permanent.

*(Reutilizați captura de ecran pentru "Setări".)*

## Concluzie
Aplicația "To Do List for Students" îndeplinește toate cerințele UI/UX și ale laboratoarelor PIUG. Design-ul este modern, funcționalitățile sunt intuitive, iar principiile de proiectare sunt respectate. Urmează testarea în Laboratorul 5 pentru a evalua uzabilitatea.

*(Opțional: Adăugați o captură de ecran generală a aplicației, e.g., pagina "Acasă" după autentificare.)*