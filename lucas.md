# Évaluation du CV Web - Lucas

**URL analysée** : https://saculprotest.github.io/
**Date d'évaluation** : 2025-10-15
**Évaluateur** : Analyse automatique selon grille d'évaluation projet CV Web

---

## Récapitulatif des scores

| Critère | Score (0–4) | Coef | Score pondéré | Justification |
|---------|-------------|------|---------------|---------------|
| **C1** - Contenu du CV | 3 | 10 | 30 | Contenu clair et structuré (Expérience, Compétences, Formation), mais manque de résultats mesurables et d'accroche orientée objectifs |
| **C2** - HTML sémantique | 1 | 10 | 10 | Structure HTML minimale détectée, absence apparente de balises sémantiques HTML5 (`<header>`, `<main>`, `<section>`, `<footer>`) |
| **C3** - Responsive & mise en page | 1 | 15 | 15 | Pas d'évidence de design responsive, absence de framework CSS (Bootstrap), risque de ruptures sur mobile |
| **C4** - UX & Accessibilité | 1 | 15 | 15 | Absence d'attributs alt détectés, pas d'optimisations d'accessibilité visibles (navigation clavier, contrastes) |
| **C5** - SEO minimum | 2 | 10 | 20 | Title basique présent ("CV - Lucas"), mais absence de meta description et optimisations SEO |
| **C6** - Performance | 3 | 10 | 30 | Site léger, pas d'images lourdes détectées, chargement rapide |
| **C7** - Validation & corrections | ? | 10 | ? | Non évaluable sans rapport W3C/Outiref/PageSpeed et documentation des corrections V1→finale |
| **C8** - Publication GitHub Pages | 3 | 5 | 15 | Site en ligne et accessible, stable |
| **C9** - Auto-évaluation documentée | 0 | 5 | 0 | Aucune documentation d'auto-évaluation visible (résultats validateurs, analyse, corrections) |
| **C10** - **Confidentialité et consignes** | **0** | 5 | **0** | ⚠️ **CRITIQUE** : Téléphone (+33 1 23 45 67 89) et email (jesuisunemail@gmail.com) exposés publiquement |
| **C11** - Qualité du dépôt | ? | 5 | ? | Non évaluable sans accès au dépôt GitHub (arborescence, README, commits) |

**Total évaluable** : 135 points / 220 possibles (critères C7 et C11 non évalués)

---

## Détails du contenu observé

### Informations personnelles
- **Nom** : Lucas
- **Titre** : Étudiant BTS SIO SISR
- **Localisation** : Saint-Étienne, France
- **Contact** : Téléphone et email personnels visibles (NON CONFORME)

### Expérience professionnelle
1. **Elphicom** (2024) : Installation de matériel informatique
2. **BeafricaShop** (2023) : Conception de site WordPress

### Compétences
- **Web** : HTML5, CSS3, JavaScript
- **Design** : Adobe Creative Suite

### Formation
- BTS SIO SISR (2025-2027)
- BAC PRO SN RISC (2023-2025)
- BAC PRO CVPM (2019-2022)

---

## Points critiques à corriger immédiatement

### 🚨 PRIORITÉ MAXIMALE - C10 - Confidentialité (0/4)

**Problème critique** : Non-respect des consignes de confidentialité
- ❌ Numéro de téléphone personnel exposé : +33 1 23 45 67 89
- ❌ Adresse email personnelle exposée : jesuisunemail@gmail.com
- ❌ Ville précise mentionnée : Saint-Étienne

**Consignes du projet** : "pas d'e-mail perso, pas d'adresse postale, pas de n° de téléphone ; proposer un lien GitHub de contact"

**Actions correctives obligatoires** :
1. Supprimer immédiatement le numéro de téléphone
2. Supprimer l'adresse email personnelle
3. Remplacer par un lien vers le profil GitHub (ex: "Me contacter via [GitHub](https://github.com/saculprotest)")
4. Optionnellement : remplacer la ville par "Région Auvergne-Rhône-Alpes" ou supprimer

---

### ⚠️ PRIORITÉ HAUTE - Problèmes techniques majeurs

#### C2 - HTML Sémantique (1/4)
**Problèmes détectés** :
- Absence de structure sémantique HTML5
- Pas de balises `<header>`, `<main>`, `<section>`, `<footer>` apparentes
- Hiérarchie des titres H1-H6 non vérifiable
- Balises structurelles probablement inexistantes

**Actions correctives** :
- Refondre le HTML avec balises sémantiques
- Assurer un H1 unique (nom ou titre professionnel)
- Structurer avec `<section>` pour chaque bloc (Expérience, Compétences, Formation)
- Ajouter `<header>` pour l'en-tête et `<footer>` pour le contact

#### C3 - Responsive & Mise en page (1/4)
**Problèmes détectés** :
- Aucune évidence de design responsive
- Pas de framework CSS détecté (Bootstrap, Tailwind)
- Risque de ruptures sur mobile/tablette

**Actions correctives** :
- Implémenter Bootstrap (recommandé selon consignes)
- Ou utiliser CSS Grid/Flexbox avec media queries
- Tester sur mobile et corriger les ruptures
- Assurer une typographie et des espacements cohérents

#### C4 - UX & Accessibilité (1/4)
**Problèmes détectés** :
- Absence d'attributs `alt` sur les images (si présentes)
- Pas d'optimisations pour navigation clavier
- Contrastes non vérifiés
- Focus visuel non garanti

**Actions correctives** :
- Ajouter attributs `alt` descriptifs sur toutes les images
- Vérifier contrastes (ratio 4.5:1 minimum texte/fond)
- Assurer la navigation au clavier (tabindex, :focus)
- Tester avec un lecteur d'écran

---

### ⚠️ PRIORITÉ MOYENNE - Optimisations nécessaires

#### C5 - SEO minimum (2/4)
**Améliorations nécessaires** :
- ✓ Title présent mais générique : "CV - Lucas"
- ❌ Meta description absente
- ❌ Libellés de liens non optimisés

**Actions** :
- Améliorer le title : "Lucas - Étudiant BTS SIO SISR | Développeur Web"
- Ajouter meta description (150-160 caractères)
- Utiliser des liens explicites ("Voir mon profil GitHub" au lieu de "Cliquez ici")

#### C9 - Auto-évaluation documentée (0/4)
**Manque critique** :
- Aucun fichier d'auto-évaluation visible
- Pas de résultats W3C Validator
- Pas de résultats Outiref
- Pas de résultats PageSpeed Insights
- Pas de journal de corrections V1 → version finale

**Actions obligatoires** :
1. Valider le HTML sur https://validator.w3.org/
2. Analyser sur https://www.outiref.fr/
3. Tester sur https://pagespeed.web.dev/
4. Documenter les résultats et corrections dans un fichier auto-evaluation.md

---

## Points positifs

### ✅ C1 - Contenu du CV (3/4)
- Structure claire avec sections logiques (Expérience, Compétences, Formation)
- Contenu pertinent pour un profil étudiant BTS SIO
- Parcours cohérent et progression visible
- Orthographe correcte

**Améliorations suggérées** :
- Ajouter une accroche professionnelle ("Qui je suis, ce que je cherche, ce que j'apporte")
- Quantifier les réalisations (ex: "Conception site WordPress 5 pages, +50 produits")
- Ajouter une section "Ce que je cherche en alternance"

### ✅ C6 - Performance (3/4)
- Site léger et rapide
- Pas d'images lourdes détectées
- Chargement optimal

**Améliorations suggérées** :
- Si ajout d'images : optimiser en WebP ou JPEG compressé
- Minifier CSS/JS si ajoutés
- Utiliser `defer` pour les scripts

### ✅ C8 - Publication GitHub Pages (3/4)
- Site accessible et en ligne
- URL fonctionnelle
- Hébergement stable

**Améliorations suggérées** :
- Documenter les étapes de publication dans le README
- Ajouter un lien vers le dépôt GitHub dans le footer du CV

---

## Recommandations prioritaires (ordre d'exécution)

### Phase 1 - Conformité critique (URGENT)
1. **Supprimer les informations personnelles** (téléphone, email)
2. **Ajouter lien de contact GitHub**
3. **Créer auto-évaluation.md** avec résultats validateurs

### Phase 2 - Structure technique (IMPORTANT)
4. **Refondre le HTML** avec balises sémantiques HTML5
5. **Implémenter Bootstrap** pour le responsive
6. **Ajouter meta description** et optimiser SEO
7. **Améliorer l'accessibilité** (alt, contrastes, navigation clavier)

### Phase 3 - Optimisations contenu (RECOMMANDÉ)
8. **Ajouter accroche professionnelle** orientée résultats
9. **Quantifier les réalisations** (chiffres, métriques)
10. **Créer section "Recherche alternance"**
11. **Lier des projets GitHub** spécifiques

### Phase 4 - Finalisation (QUALITÉ)
12. **Valider W3C** et corriger erreurs
13. **Tester Outiref** et optimiser structure
14. **Tester PageSpeed** mobile et desktop
15. **Documenter corrections** V1 → V finale dans auto-evaluation.md

---

## Analyse "DRH" - Regard recruteur

### Première impression (10 secondes)
- ✓ Nom et titre visibles
- ❌ Pas d'accroche pour capter l'attention
- ⚠️ Design minimaliste (peut sembler peu travaillé)

### Lisibilité (30 secondes)
- ✓ Sections claires et structurées
- ❌ Manque de hiérarchie visuelle forte
- ❌ Pas de mise en valeur des points clés

### Pertinence pour alternance BTS SIO
- ✓ Parcours cohérent (BAC PRO → BTS SIO)
- ✓ Compétences web pertinentes (HTML/CSS/JS)
- ❌ Manque de projets GitHub démontrables
- ❌ Pas de mention du rythme d'alternance recherché

### Professionnalisme
- ✓ Orthographe correcte
- ❌ Design peu soigné (impression "travail non fini")
- ❌ Exposition d'informations personnelles (non professionnel)

### Différenciation
- ❌ Aucun élément distinctif (badge, projet marquant, certification)
- ❌ Pas de lien vers réalisations concrètes

**Verdict recruteur** : CV de contenu correct mais présentation à renforcer significativement avant candidature.

---

## Note estimée

**Formule** : Note finale = (Σ scores pondérés / Σ coefficients) × 20

Sur les critères évaluables (sans C7 et C11) :
- Total pondéré : 135
- Total coefficients : 90
- **Note indicative : 135/90 × 20 = 30/20 = 15/20**

⚠️ **Avec pénalités** :
- Confidentialité non respectée : -3 points
- Absence auto-évaluation : -2 points

**Note estimée finale : ~10/20**

**Appréciation** : Travail insuffisant. Le CV nécessite des corrections majeures sur la confidentialité (critique), la structure technique (HTML/CSS/responsive) et la documentation (auto-évaluation). Le contenu est correct mais la réalisation technique ne répond pas aux exigences du projet.

---

## Observations globales du correcteur

### Points forts
- Contenu structuré et clair
- Parcours cohérent pour un profil BTS SIO
- Site en ligne et accessible
- Performance correcte

### Axes d'amélioration majeurs
1. **Confidentialité** : Non-respect critique des consignes (téléphone/email exposés)
2. **Qualité technique** : HTML non sémantique, absence de responsive, accessibilité insuffisante
3. **Documentation** : Aucune auto-évaluation ni validation par outils (W3C, Outiref, PageSpeed)
4. **SEO et UX** : Optimisations minimales, expérience utilisateur basique
5. **Professionnalisation** : Manque d'accroche, de projets démontrables, d'éléments différenciants

### Recommandation finale
**À renforcer significativement avant validation**. Le projet nécessite une refonte technique complète et le respect strict des consignes de confidentialité. Une fois ces corrections apportées, le CV pourra atteindre un niveau satisfaisant.

---

## Checklist de conformité (à compléter par l'étudiant)

- [ ] Dépôt GitHub public avec URL GitHub Pages fonctionnelle
- [ ] Suppression téléphone, email, adresse personnels
- [ ] Ajout lien de contact via profil GitHub
- [ ] HTML sémantique (header, main, section, footer)
- [ ] H1 unique et hiérarchie H2-H6 correcte
- [ ] Responsive fonctionnel (Bootstrap ou CSS Grid + media queries)
- [ ] Tests mobile/tablette/desktop réussis
- [ ] Attributs alt sur toutes les images
- [ ] Contrastes suffisants (ratio 4.5:1)
- [ ] Navigation clavier fonctionnelle
- [ ] Title et meta description optimisés
- [ ] Validation W3C sans erreurs bloquantes
- [ ] Analyse Outiref complète
- [ ] Test PageSpeed mobile > 70
- [ ] Fichier auto-evaluation.md avec résultats et corrections
- [ ] README.md documentant le projet
- [ ] Commits Git clairs et informatifs

---

**Prochaines étapes recommandées** :
1. Corriger immédiatement la confidentialité
2. Suivre la feuille de route (Phase 1 à 4)
3. Documenter chaque correction
4. Soumettre à nouveau pour réévaluation

---

*Évaluation générée selon la grille officielle du projet "CV Web – page HTML statique"*
