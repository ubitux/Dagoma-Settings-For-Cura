## Vous possédez un imprimante 3D de chez DAGOMA et vous désirez passer de CuraByDagoma à Cura 2.3.

##ATTENTION CERTAINS PARAMÈTRES NE SONT PAS ENCORE TRANSFÉRÉS, CES FICHIERS SONT PARTAGÉS POUR ÊTRE TESTÉS.

Voici les fichiers qui vous permettront de retrouver les paramètres par défaut de CuraByDagoma dans Cura version 2.3

Les fichiers sont à copier dans le dossier d'installation de Cura.

Par défaut, sous Windows 64bits :
`C:\Program Files\Cura 2.3`

- Les paramètres des imprimantes :
  - `.\resources\definitions\*.def.json`
- Le modèle 3D des imprimantes :
  - `.\resources\meshes\*_plateform.stl`
- Les paramètres de qualité d'impression :
  - `.\resources\quality\dagoma_*\*.inst.cfg`
- Les paramètres des différents filaments :
  - `.\resources\materials\*.xml.fdm_material`

**Attention ces fichiers vous sont fournis sans garantie**. Je ne pourrais être tenu responsable d'un quelconque dommage causé à votre imprimante 3D. A vous de bien vérifier les paramètres avant de lancer l'impression.

##ASTUCE :

Si vous souhaitez accélérer le chargement de Cura, vous pouvez supprimer les imprimantes que vous n'utilisez pas.
`.\resources\definitions\*.def.json` **SAUF fdmprinter.def.json** et **custom.def.json** (si vous souhaitez pouvoir ajouter une imprimante personnalisable.)
