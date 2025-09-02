# Switzea Projektplanlægning

> Kraftfuld projektplanlægningsapp til håndværkere med integreret tidslinje, opgavestyring og PDF-eksport til kunder.

## 🚀 Demo

**Live Demo:** [Klik her for at teste appen](https://mjoxp.github.io/Project-planner/)

## 📋 Funktioner

### ✅ **Håndværker Management**
- Alle håndværkere placeret i dedikeret venstre kolonne
- Drag-and-drop sortering af håndværker-rækker
- Tilføj/slet håndværkere med farvekodet system

### ⏰ **Timeline & Opgaver**
- Funktionel timeline-grid med dag-for-dag visning
- Drag-and-drop opgaver mellem håndværkere og dage
- Halv/hel dag funktionalitet med visuel forskel
- Opgaver kan KUN placeres inden for projektets uger
- Klik på tomme celler for at oprette nye opgaver

### 💾 **Data & Funktionalitet**
- Gem/Indlæs projekter til localStorage
- Fortryd/Gendan (Ctrl+Z/Ctrl+Y) med fuld historie
- Slet opgave-funktion med sikkerhedsbekræftelse
- PDF eksport af professionel kundevisning

### 📱 **Brugeroplevelse**
- Intuitivt design optimeret til håndværkere
- Touch-venligt til tablets på byggepladser
- Tastatur-genveje (Ctrl+Z, Ctrl+Y, Ctrl+S)
- Toast-notifikationer for brugerfeedback
- Fuldt responsivt design

## 🏗️ Baseret på Capellas Allé Projektet

Appen kommer forudkonfigureret med:
- ✅ Projektinfo fra renoverings-tilbudet
- ✅ Alle 8 opgaver fra projektet
- ✅ Håndværker-setup (Byggeleder, Tømrer, Elektriker, VVS-montør)  
- ✅ Realistiske tidsestimater og afhængigheder

## 🛠️ Teknisk Setup

### Lokal Udvikling
1. Clone dette repository
2. Åbn `index.html` direkte i browser
3. Alle funktioner virker uden server eller installation

### GitHub Pages Deployment
1. Upload filer til dit GitHub repository
2. Aktivér GitHub Pages i repo settings
3. Vælg "Deploy from main branch"
4. Din app er tilgængelig på: `https://DIT-BRUGERNAVN.github.io/REPO-NAVN/`

## 📊 Projektdata Struktur

```json
{
  "project": {
    "name": "Capellas Allé 38 Renovering",
    "address": "Capellas Allé 38, 2770 Kastrup",
    "customer": "Maria Josefina Herrera og Jose Eduardo Gran",
    "totalValue": "99.100 DKK"
  },
  "craftsmen": [
    {"name": "Byggeleder", "color": "#4A90E2"},
    {"name": "Tømrer", "color": "#8B4513"},
    {"name": "Elektriker", "color": "#FFD700"},
    {"name": "VVS-montør", "color": "#32CD32"}
  ]
}
```

## 🎯 Hovedfunktioner

| Funktion | Beskrivelse | Status |
|----------|-------------|---------|
| Håndværker i kolonne | Alle håndværkere kun i venstre kolonne | ✅ |
| Drag-and-drop opgaver | Flyt opgaver mellem dage og håndværkere | ✅ |
| Halv/hel dag | Visuel forskel på opgavestørrelser | ✅ |
| Ugebegrænsning | Opgaver kun indenfor valgte uger | ✅ |
| Gem/Indlæs | Persistent storage af projekter | ✅ |
| PDF eksport | Professionel kundevisning | ✅ |
| Undo/Redo | Fuld historik af ændringer | ✅ |

## 🔧 Brugervejledning

### Opret Opgave
1. Klik på en tom celle i tidslinjen
2. Udfyld opgavedetaljer i popup
3. Vælg håndværker, prioritet og varighed
4. Klik "Gem opgave"

### Flyt Opgave  
1. Træk opgaven til ønsket position
2. Slip på ny celle (må ikke overstige ugegrænser)
3. Opgaven flyttes automatisk

### Håndværker Management
1. Tilføj håndværkere via "+ Tilføj" knappen
2. Træk håndværkere for at ændre rækkefølge
3. Slet håndværkere (fjerner også deres opgaver)

### Eksporter til Kunde
1. Klik "👥 Kunde" eller "📄 PDF" knappen  
2. Professionel PDF genereres automatisk
3. Print eller gem til deling med kunde

## 📱 Responsive Design

- **Desktop:** Fuld funktionalitet med alle detaljer
- **Tablet:** Touch-optimeret til byggeplads-brug
- **Mobile:** Kompakt layout med scrolling

## 🔒 Data Sikkerhed

- Alt data gemmes lokalt i browserens localStorage
- Ingen data sendes til eksterne servere
- Projekter kan eksporteres som backup

---

**Udviklet af:** Switzea ApS  
**Version:** 2.0  
**Sidste opdatering:** September 2025

## 📞 Support

For spørgsmål eller fejlrapporter, kontakt Switzea ApS.
