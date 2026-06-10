# Saldato — Business Plan

> **"Il preventivo è gratis. Il mio tempo no."**

---

## 1. Problema

Gli artigiani dell'edilizia leggera (ristrutturazioni, cartongesso, tinteggiatura, infissi, impianti) in Italia mandano preventivi e poi:
- Il 50-70% dei clienti **sparisce** senza rispondere
- L'artigiano **non sa chi lo sta ignorando** finché non è troppo tardi
- Perde tempo (sopralluoghi, preventivi, telefonate) e soldi (materiali acquistati) su lavori che non si concretizzano
- La sera, dopo una giornata in cantiere, **rincorre manualmente** chi non risponde

**Dati a supporto:**
- Il cash flow timing è la fonte primaria di ansia per il 41% degli imprenditori (CrowdfundInsider 2026)
- Il 56% delle piccole imprese ha crediti non incassati, saldo medio 17.500$ (Intuit)
- In Italia i tempi medi di pagamento per micro-imprese sono 50+ giorni (Cerved/Il Sole 24 Ore 2025)
- La quota di aziende che paga puntuale è in calo (Cribis/CRIF 2025)
- Il tasso di conversione preventivi nel settore edile è storicamente sotto il 30%

---

## 2. Soluzione

**Saldato** è un'app mobile-first che permette all'artigiano di:
1. Creare e mandare preventivi professionali in 30 secondi (via WhatsApp)
2. Vedere in tempo reale chi apre, chi legge, chi sparisce
3. Attivare solleciti automatici che riportano i fantasmi a rispondere
4. Incassare l'acconto dal link (opzionale) o gestirlo come preferisce

**Non è un gestionale. Non è un sistema di fatturazione. È un filtro anti-perditempo.**

---

## 3. Target

### Cliente ideale
- Artigiano edile, ditta individuale o max 3-4 persone
- Lavora con privati (B2C)
- Preventivo medio: 2.000–15.000€
- Manda 8-15 preventivi al mese
- Zona: Nord Italia (Lombardia, Veneto, Emilia-Romagna, Piemonte)
- Ha partita IVA, fattura almeno parte del lavoro
- NON ha una segretaria o un ufficio strutturato

### Mestieri prioritari
1. Edile / Ristrutturazioni generali
2. Cartongessista / Controsoffittista
3. Imbianchino / Tinteggiatore
4. Posatore infissi / serramenti
5. Idraulico (interventi grandi, non pronto intervento)
6. Elettricista (rifacimenti impianto)
7. Climatizzazione

### Dimensione mercato (Italia)
- ~320.000 imprese artigiane nel settore costruzioni (Confartigianato)
- Target raggiungibile (Nord Italia, digitalmente attivi): ~80.000
- 1% penetrazione = 3.200 utenti = ~99.000€/mese di revenue

---

## 4. Modello di pricing

### Principio: l'artigiano non paga mai prima di vedere il risultato.

| Cosa | Costo | Nota |
|---|---|---|
| Creare e mandare preventivi | **Gratis** per sempre | Valore immediato, zero barriera |
| Vedere quanti fantasmi hai (numero) | **Gratis** per sempre | Crea il prurito |
| Scoprire CHI sono i fantasmi (nome, timestamp) | **5€** per fantasma svelato | L'artigiano decide se gestirlo lui |
| Solleciti automatici che riportano il fantasma | **10€** per fantasma recuperato | Paghi solo se il cliente TORNA e CONFERMA |
| Incasso acconto digitale (carta/Satispay/SEPA) | **1.9%** commissione | Opzionale, l'artigiano sceglie |
| **Tetto mensile** | **49€/mese massimo** | Mai di più, anche con 20 recuperi |

### Definizione di "fantasma recuperato"
Un cliente che:
1. Non ha interagito col preventivo per 48+ ore
2. Ha ricevuto un sollecito automatico da Saldato
3. Dopo il sollecito, torna e conferma il preventivo (entro 7 giorni)

Se il cliente conferma subito (entro 48h, senza solleciti) → l'artigiano non paga niente.

### Ingresso: primi 10 lavori completamente gratuiti
Nessuna carta di credito richiesta. L'artigiano vede i risultati con i suoi occhi prima di pagare qualsiasi cosa.

---

## 5. Unit Economics

### Revenue per utente (ARPU mensile)

| Voce | Calcolo | €/mese |
|---|---|---|
| Fantasmi recuperati | 1.5 recuperi × 10€ | 15€ |
| Fantasmi svelati | 1 svelamento × 5€ | 5€ |
| Commissione incasso digitale | 30% utenti × 1.5 lavori × 1.050€ acconto × 1.9% | 9€ |
| **ARPU medio** | | **~29€/mese** |

### Costi per utente

| Voce | €/mese |
|---|---|
| Infrastruttura (hosting, DB) | ~1.5€ |
| WhatsApp Business API (~15 msg/utente × 0.08€) | ~1.2€ |
| Payment processing (Stripe ~1.4% incluso nel 1.9%) | ~0.5€ netto |
| Supporto (proporzionale) | ~1.3€ |
| **Totale costo variabile** | **~4.5€/utente** |

### Margine per utente
**ARPU 29€ − costo variabile 4.5€ = margine lordo ~24.5€/utente/mese**

### Margine lordo percentuale: ~84%

---

## 6. Break-even

### Costi fissi mensili (fase iniziale)

| Voce | €/mese |
|---|---|
| Infrastruttura fissa (server, dominio, monitoring) | 200€ |
| Tuo tempo (costo opportunità) | 2.000€ |
| Marketing / ads | 300€ |
| Tool (analytics, email, vari) | 100€ |
| **Totale** | **2.600€/mese** |

### Break-even
**2.600€ ÷ 24.5€ = ~106 utenti attivi paganti**

---

## 7. Piano di crescita (12 mesi)

| Mese | Utenti attivi | Revenue mensile | Cumulato | Note |
|---|---|---|---|---|
| 1 | 5 | 145€ | -2.455€ | Beta tester dalle interviste |
| 2 | 15 | 435€ | -4.620€ | Passaparola + fine trial 10 lavori |
| 3 | 35 | 1.015€ | -6.205€ | Primi ads Facebook/IG locali |
| 4 | 60 | 1.740€ | -7.065€ | Referral "porta un collega" |
| 5 | 90 | 2.610€ | -7.055€ | Quasi break-even |
| **6** | **110** | **3.190€** | **-6.465€** | **Break-even mensile superato** |
| 7 | 135 | 3.915€ | -5.150€ | Crescita organica |
| 8 | 165 | 4.785€ | -2.965€ | |
| 9 | 200 | 5.800€ | +235€ | **Break-even cumulato** |
| 10 | 240 | 6.960€ | +4.595€ | |
| 11 | 280 | 8.120€ | +10.115€ | |
| **12** | **330** | **9.570€** | **+17.085€** | |

### Assunzioni di crescita
- Mese 1-2: organico puro (interviste → beta tester)
- Mese 3+: budget ads 300€/mese, CAC ~25€ (gruppi FB artigiani, IG locale)
- Churn mensile: 5% (basso perché pay-per-result = nessun motivo di disdire)
- Crescita organica/referral: +15% mese su mese dopo il mese 4

---

## 8. Canali di acquisizione

### Fase 1 (mese 1-3): Validazione e primi utenti
- 25 interviste → 10-15 beta tester gratis
- Gruppi Facebook artigiani (Brianza, Lombardia, Veneto)
- Passaparola: "porta un collega che bestemmia sui preventivi"
- Post organici con il claim nei gruppi

### Fase 2 (mese 3-6): Trazione
- Facebook/Instagram ads geo-targetizzati (Lombardia, Veneto)
- Contenuti video (30 sec): "Questo artigiano ha 4 fantasmi. Guarda cosa succede quando clicca."
- Partnership con rivendite di materiali edili (volantino in negozio)
- Presenza a fiere locali del settore edile

### Fase 3 (mese 6-12): Scala
- Referral program: porta un collega → entrambi avete 5 lavori extra gratis
- Content marketing: storie di artigiani che hanno recuperato lavori
- Espansione geografica (Centro Italia)
- Partnership con commercialisti e associazioni CNA/Confartigianato

---

## 9. Roadmap prodotto

### MVP (mese 1-2)
- [ ] Creazione preventivo mobile (PWA)
- [ ] Invio link via WhatsApp (deep link)
- [ ] Tracking apertura link (pixel/redirect)
- [ ] Dashboard fantasmi (numero sfocato + nomi blurrati)
- [ ] Sblocco nome (5€ via Stripe)
- [ ] Vista cliente: accettazione preventivo

### V1.0 (mese 3-4)
- [ ] Solleciti automatici via WhatsApp Business API
- [ ] Pay-per-result: addebito automatico solo su recupero confermato
- [ ] Incasso acconto digitale (Stripe Connect)
- [ ] Tetto mensile 49€

### V1.5 (mese 5-8)
- [ ] App nativa (iOS + Android) o PWA installabile
- [ ] Template preventivi per mestiere
- [ ] Storico e statistiche (tasso conversione, tempo medio risposta)
- [ ] Notifiche push real-time ("Il tuo fantasma ha aperto il link!")
- [ ] Sollecito saldo a fine lavori

### V2.0 (mese 9-12)
- [ ] AI: suggerimento prezzo basato su storico zona/mestiere
- [ ] Firma digitale del preventivo
- [ ] Integrazione con FattureInCloud/Aruba per emissione fattura post-conferma
- [ ] Referral program in-app
- [ ] Multi-lingua (per espansione EU)

---

## 10. Vantaggi competitivi (Moat)

| Vantaggio | Perché è difendibile |
|---|---|
| **Pay-per-result** | Nessun competitor in Italia offre questo modello per artigiani. Crea fiducia istantanea. |
| **Dati di settore** | Accumuliamo tassi di ghosting/recupero per zona, mestiere, importo. Nessuno ha questi dati. |
| **Effetto LinkedIn Premium** | Il "numero rosso dei fantasmi" crea un prurito psicologico che spinge all'azione (e al pagamento). |
| **Viralità bilaterale** | Il cliente riceve il link di Saldato → lo vede funzionare → lo suggerisce al suo artigiano per un altro lavoro. |
| **Basso churn strutturale** | Non paghi se non usi → non hai motivo di disdire → l'app resta installata → quando hai un mese pieno, paghi. |

---

## 11. Competitor e posizionamento

| Player | Cosa fa | Prezzo | Per chi | Perché non è una minaccia |
|---|---|---|---|---|
| **Jobber** | Gestionale completo field service | 49-139$/mese fisso | Aziende con segretaria | Troppo complesso, troppo caro, non in italiano |
| **Housecall Pro** | Gestionale + marketing | 79-189$/mese fisso | Aziende US strutturate | Zero presenza in Italia, overkill |
| **ServiceTitan** | Enterprise field service | 300+$/mese | Grandi aziende (20+ persone) | Carro armato per fare la spesa |
| **FattureInCloud** | Fatturazione elettronica | 8-30€/mese | Tutti | Non fa preventivi smart né tracking |
| **ProntoPro** | Lead generation marketplace | Pay-per-lead (crediti) | Artigiani che cercano clienti | Risolve "trovare clienti", non "gestirli". Odiato. |
| **NudgeQuote** | Follow-up preventivi (solo Jobber) | Add-on | Utenti Jobber | Solo anglofono, dipende da Jobber |
| **Saldato** | Anti-ghosting + incasso | Pay-per-result, max 49€ | Micro-artigiano italiano solo | Unico posizionato qui |

---

## 12. Rischi e mitigazioni

| Rischio | Prob. | Impatto | Mitigazione |
|---|---|---|---|
| Artigiano bypassa (chiama a mano dopo aver visto il numero) | Alta | Medio | Il nome è sfocato — deve pagare per sapere chi. E il sollecito auto funziona meglio della sua chiamata. |
| Tasso di recupero più basso del 30% | Media | Alto | A/B test su testi e timing solleciti. Iterazione rapida. |
| WhatsApp blocca messaggi commerciali | Bassa | Alto | Fallback su SMS + email. Template pre-approvati da Meta. |
| Competitor italiano copia | Media | Medio | First-mover, community, dati accumulati, brand riconoscibile. |
| Artigiani troppo "analogici" | Media | Medio | Focus su < 45 anni, digitalmente attivi (usano già WhatsApp per lavoro). |
| Regolamentazione privacy (GDPR) | Bassa | Medio | Consenso esplicito dal cliente che riceve il link. Cookie tecnici per tracking apertura. |

---

## 13. Metriche chiave (KPI)

### Acquisizione
- CAC (costo acquisizione cliente)
- Tasso di conversione trial → pagante
- Tempo medio da iscrizione a primo pagamento

### Engagement
- Preventivi mandati/mese per utente
- % utenti che vedono fantasmi (quasi tutti)
- % che sblocca o attiva solleciti (conversione interna)

### Revenue
- ARPU (average revenue per user)
- MRR (monthly recurring revenue)
- Tetto raggiunto (% utenti che arrivano a 49€/mese = segnale di valore percepito alto)

### Retention
- Churn mensile
- NPS (Net Promoter Score)
- % utenti attivi dopo 3 mesi

### Prodotto
- Tasso di recupero fantasmi (% fantasmi che tornano dopo sollecito)
- Tempo medio di recupero (ore tra sollecito e conferma)
- Tasso di conferma con vs senza Saldato (il delta è il valore)

---

## 14. Exit / Scenari futuri

| Scenario | Timeline | Note |
|---|---|---|
| Lifestyle business (1 persona, 300 utenti) | 12 mesi | 9.500€/mese, ~6.000€ netto. Lavori 20h/settimana. |
| Scala Italia (3 persone, 2.000 utenti) | 24 mesi | 58.000€/mese. Assumi dev + sales. |
| Espansione EU (DE, ES, FR) | 36 mesi | Stesso problema ovunque, localizzazione. |
| Acquisizione da player FSM | 36-48 mesi | Jobber/ServiceTitan cercano il mercato EU micro. I tuoi dati valgono. |
| Evoluzione a "Stripe per artigiani" | 48 mesi | Dal preventivo alla fattura: controlli l'intero flusso monetario. |

---

## 15. Prossimi passi immediati

1. **Settimana 1:** 25 interviste con artigiani edili (script pronto)
2. **Settimana 2:** Analisi risultati. GO/STOP/PIVOT.
3. **Settimana 3-4:** MVP tecnico (PWA + tracking link + dashboard)
4. **Settimana 5-6:** Beta con 10 artigiani (gratis)
5. **Settimana 7-8:** Primo pagamento, iterazione pricing

---

*Documento vivo. Aggiornare dopo ogni ciclo di interviste e dopo ogni milestone.*
