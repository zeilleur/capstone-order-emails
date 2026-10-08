# From order email to purchase order

AI Systems capstone (HEC Paris). A Python pipeline that turns free-text customer order emails into purchase orders: structured extraction (LLM + strict schema), catalogue RAG (hybrid search + LLM choice), business checks in code, and a drafted reply. Uncertain emails go to human review.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zeilleur/capstone-order-emails/blob/main/capstone_bons_de_commande.ipynb)

**Run it:** open the notebook in Colab, click *Run all*, and paste an API key when asked (an OpenRouter key `sk-or-...` or an OpenAI key `sk-...`). The data in `data/` is downloaded automatically.

`data/`: a fictional catalogue (127 products), 10 clients and 30 hand-labelled test emails.
