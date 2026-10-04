# BÃ¡o cÃ¡o BÃ i 3: Cáº¥u hÃ¬nh xÃ¡c thá»±c SSH vÃ  Äáº©y dá»± Ã¡n lÃªn GitHub

## QuÃ¡ trÃ¬nh táº¡o khÃ³a SSH Ed25519
```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
# Nháº­p vá»‹ trÃ­ lÆ°u (máº·c Ä‘á»‹nh: ~/.ssh/id_ed25519)
# Nháº­p passphrase (tÃ¹y chá»n)
```

## LiÃªn káº¿t remote repository
```bash
git remote set-url origin git@github.com:mtuyen260609/IT209-ss4-b3.git
```

## Kiá»ƒm tra cáº¥u hÃ¬nh remote URL
```bash
git remote -v
origin  git@github.com:mtuyen260609/IT209-ss4-b3.git (fetch)
origin  git@github.com:mtuyen260609/IT209-ss4-b3.git (push)
```

## ÄÆ°á»ng dáº«n URL cá»§a kho lÆ°u trá»¯ GitHub
`git@github.com:mtuyen260609/IT209-ss4-b3.git`
