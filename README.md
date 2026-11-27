# onespear-data — sources et licences des données

> Jeux de données republiés pour l'application OneSpear. **Chaque dossier garde la
> licence de sa source** ; OneSpear n'en est que le redistributeur / transformateur.
> Aucune garantie : données indicatives, ne remplacent pas les documents officiels
> (SHOM, préfectures maritimes, Météo-France). Contact : espinasseb@gmail.com
> — tout producteur souhaitant une attribution corrigée ou un retrait : écrire, ce
> sera fait.
>
> **Données modifiées.** Les fichiers publiés ici sont des produits DÉRIVÉS
> (rééchantillonnage, analyse harmonique, fusion de sources, conversion en
> images) réalisés par OneSpear : ce ne sont pas les données d'origine. **Les
> producteurs cités ne cautionnent ni ces traitements, ni l'application, ni
> l'usage qui en est fait** ; leur mention n'implique aucun partenariat ni
> caractère officiel. Les données d'origine se trouvent chez chaque producteur.
>
> Produits Copernicus Marine (licence lue le 14/11/2026, art. 2.4) : produits
> dérivés = *Generated using E.U. Copernicus Marine Service Information; DOI* ;
> produits non modifiés = *E.U. Copernicus Marine Service Information; DOI*.
> Foudre : *Contains modified EUMETSAT Meteosat product 2026* (CC BY 4.0).

| Dossier | Contenu | Source / attribution | Licence |
|---|---|---|---|
| `buoys/` | Bouées houle/vent/température (historiques inclus) | © Candhis — Cerema ; NDBC — NOAA ; Copernicus Marine IN SITU (DOI 10.48670/moi-00043, moi-00045, moi-00036) ; AODN ; Queensland Government ; Météo-France | Etalab 2.0 · domaine public (NDBC) · CC-BY 4.0 (AODN, Queensland) · Copernicus (cf. conditions du service) |
| `weather/`, `wind/` | Grille de vent/houle, vent mondial | Open-Meteo ; NOAA/NCEP GFS | CC-BY 4.0 · domaine public |
| `waves/` | Houle mondiale et côtière | Generated using E.U. Copernicus Marine Service Information (MFWAM, DOI 10.48670/moi-00017) ; © ECMWF (WAM) ; source : Météo-France (WW3, API Modèles de vague et surcote) | Licence Copernicus Marine · CC BY 4.0 (ECMWF) · Licence Ouverte Etalab 2.0 (Météo-France : source ET date de dernière mise à jour à mentionner) |
| `transfer/` | Tables de transfert de houle (produit dérivé) | © Ifremer — ResourceCODE, DOI 10.12770/d089a801-c853-49bd-9064-dde5808ff8d8 | **CC BY-SA 4.0** — ces tables dérivées sont publiées sous la **même** licence |
| `tide/`, `stations/` | Atlas de marée, constantes harmoniques, surcote | Dérivés de MARS/MANGA © MARC/Ifremer ; observations REFMAR © SHOM ; marégraphes IOC/VLIZ (Sea Level Station Monitoring Facility, DOI 10.14284/482) ; Copernicus | Etalab 2.0 (REFMAR) · MARC : **usage non commercial** · IOC : **usage non commercial**, données brutes non contrôlées |
| `currents/`, `regions/` | Atlas de courant (harmoniques), courant mondial | Dérivés de MARS2D © MARC/Ifremer ; Generated using E.U. Copernicus Marine Service Information (DOI 10.48670/moi-00016 monde, 10.48670/mds-00359 Méditerranée, 10.48670/moi-00027 Ibérie-Gascogne) | MARC : **usage non commercial** · licence Copernicus Marine |
| `sst/` | Température de surface, banquise | Generated using E.U. Copernicus Marine Service Information (IFREMER-ATL L4 DOI 10.48670/moi-00152, Méditerranée L4 10.48670/moi-00172, OSTIA 10.48670/moi-00165) | Licence Copernicus Marine |
| `radar/`, `lightning/`, `verif/` | Radar de pluie, PIAF, foudre | © Météo-France (API Données Publiques) ; © EUMETNET OPERA (CC BY 4.0) ; Contains modified EUMETSAT Meteosat product 2026 (MTG LI-2-LFL, donnée « Core ») | Etalab 2.0 · CC BY 4.0 · CC BY 4.0 (EUMETSAT) |
| `nav/` | AVURNAV, géo-réglementation | © Shom — Ping Info Nautique | Licence Ouverte 2.0 |
| `bathy/`, `coast/` | Profondeurs locales, masque et trait de côte | EMODnet Bathymetry Consortium (2024), EMODnet Digital Bathymetry (DTM 2024), DOI 10.12770/cf51df64-56f9-4a99-b1aa-36b8d7b743a1 — *Do not use for navigation* ; © SHOM (LITTO3D) ; © OpenStreetMap contributeurs | CC BY 4.0 (EMODnet) · Etalab 2.0 · **ODbL** (OSM) |
| `habitats/` | Nature des fonds | © OFB / Ifremer (Carpediem 2019, EUNIS) ; © Ifremer/REBENT | **CC-BY-NC** (usage non commercial) |
| `poi/` | Cales de mise à l'eau | © OpenStreetMap contributeurs ; règles d'accès compilées par OneSpear | **ODbL** — attribution « © OpenStreetMap contributors » et partage à l'identique de la base dérivée |
| `turbidity/` | Turbidité relative in situ | E.U. Copernicus Marine Service Information ; MAREL-Iroise (Ifremer, IUEM/UBO, CNRS-INSU) | Copernicus Marine |
| `zones/` | Zones réglementées | Base OneSpear (tracés établis à partir des arrêtés), **chiffrée** ; sources © Shom (Etalab 2.0) ; découpe sur la limite terre-mer © IGN BD TOPO (Licence Ouverte 2.0) et, pour la rive espagnole de la Bidassoa, © IGN España / CNIG (CC BY 4.0) | Droit des producteurs de bases (CPI L.341-1) — extraction et réutilisation interdites |
| `creneaux/`, `kill/` | Données propres à l'application | OneSpear | © Benjamin Espinasse |

Usage **non commercial** : plusieurs sources (MARC/Ifremer, Carpediem) l'imposent.
Ce dépôt ne doit donc pas être réutilisé dans un produit payant.

## Vérifié le 14/11/2026 (lecture des licences à la source)

- **Copernicus Marine** : redistribution et produits dérivés permis, gratuits,
  « for any purpose » ; crédit exigé avec DOI, visible sur la page d'accès aux
  données ; la licence impose de la répercuter et de tenir un registre d'usage.
- **EUMETSAT, foudre LI-2-LFL** : fiche du Data Store = « Free and
  unrestricted », donc donnée « Core » sous CC BY 4.0 ; redistribution et
  transformation permises, attribution seule exigée.
- **IOC/VLIZ** : usage commercial interdit ; données brutes sans contrôle
  qualité ; citation avec DOI 10.14284/482. Rien n'est écrit sur la
  redistribution : seules des constantes dérivées sont publiées ici, pas les
  observations.
- **MARC/Ifremer** : conditions déjà lues (non commercial + attribution),
  respectées. Un accord écrit pour la republication des atlas dérivés reste une
  précaution utile, pas un préalable.
- **Épaves Shom (CC BY-SA) et cales OSM (ODbL)** : fichiers distincts, pas de
  mélange dans une même base.

- **Météo-France, API « Modèles de vague et surcote »** : licence de l'API lue
  sur le portail (Licence Ouverte Etalab 2.0) ; source et date de dernière
  mise à jour à mentionner, données à ne pas dénaturer.
- **EMODnet Bathymetry** : CC BY 4.0 ; mention « do not use for navigation ».
- **DOI Copernicus** : lus dans le catalogue STAC officiel, un par produit.

- **`zones/` ne contient plus de géométrie OpenStreetMap** (14/11/2026) :
  toutes les zones sont redécoupées sur la limite terre-mer IGN BD TOPO
  (Licence Ouverte), ce qui sortait la base de l'ODbL. Restent seulement des
  emprunts non substantiels au sens d'OSM (moins de 100 objets) : deux trajets
  de vedettes (Roscoff–Batz, Saint-Malo–Dinard), un polygone (île Longue) et des
  positions d'amers lues ponctuellement.
- **Date de mise à jour Météo-France (WW3)** : chaque publication de
  `waves/coastal/manifest.json` porte l'heure du run (`run`) et de génération
  (`generated`) ; l'application affiche l'heure du run à côté de la houle
  côtière (15/11/2026).
