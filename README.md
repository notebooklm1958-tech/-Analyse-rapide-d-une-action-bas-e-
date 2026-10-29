# -Analyse-rapide-d-une-action-bas-e-
 Explications du code
1. Récupération des données (yfinance)
Le script utilise yfinance pour récupérer :
Données historiques (prix, volume).
Données financières (bilan, compte de résultat, flux de trésorerie).
Ratios (PER, ROE, etc.).
2. Analyse Technique
Tendance : Détectée via les moyennes mobiles (MA50, MA200).
Supports/Résistances : Trouvés via les extrema locaux.
Indicateurs :
RSI : Surachat (>70) ou survendu (<30).
MACD : Croisement des lignes MACD et signal.
3. Analyse Fondamentale
Bilan : Actif, passif, dette, trésorerie.
Compte de résultat : Chiffre d'affaires, bénéfice net, croissance.
Ratios :
PER : Prix/Bénéfice (idéalement <15).
ROE : Rentabilité des capitaux propres (idéalement >15%).
Dividend Yield : Rendement du dividende (idéalement >3%).
4. Prise de décision
Acheter si :
Tendance haussière ET fondamentaux solides (PER bas, ROE élevé, etc.).
Vendre si :
Tendance baissière ET fondamentaux faibles (PER élevé, ROE faible, etc.).
Attendre sinon.
5. Visualisation
Graphique des prix avec moyennes mobiles.
RSI et MACD pour confirmer les signaux.
