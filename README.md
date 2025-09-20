# 🐞 Railway $5 Credit Recreation Bug (Reported)

## 📌 Summary
I discovered a business logic bug in [Railway](https://railway.app) that allowed **$5 free trial credits** to be reissued multiple times simply by deleting and recreating an account with the same GitHub OAuth login.

What started as a $5 trial bug turned into a **$250 reward** 🎉 — thanks to responsible disclosure!

---

## 🔎 Steps to Reproduce
1. Create a new Railway account using GitHub OAuth.
2. Receive the **$5 trial credit**.
3. Consume ~90% of the credit.
4. Delete the account.
5. Recreate a new account with the **same GitHub login**.
6. Observe that the account once again receives **$5 trial credit**.

---

## ⚡ Impact
- **Type:** Business logic flaw  
- **Effect:** Unlimited free trial credits could be claimed  
- **Risk:** Potential abuse of free resources / billing fraud  
- **Severity:** Medium (financial impact, not data/security exposure)  

---

## 🛡 Responsible Disclosure
- Reported directly to Railway via **bugbounty@railway.app**.  
- Confirmed and acknowledged by their security team.  
- Railway initially clarified that sign-up abuse is monitored internally, but later rewarded me **$250** under their bounty program. 🚀  

---

## 🎉 Outcome
- Bug responsibly disclosed ✅  
- Railway rewarded me **$250** 💸  
- Lesson learned: sometimes the smallest bugs can pay the biggest dividends.  

---

## ✨ Takeaway
Turning **$5 credits → $250 reward** taught me two things:  
1. Even small logic flaws can have meaningful impact.  
2. Ethical reporting always pays off — literally. 😅  

---

## 🏆 Achievement
From **“Unlimited $5 Credits Hunter”** → **$250 Bug Bounty Winner** 🎖  

---

### 🔖 Tags
`#bugbounty` `#ethicalhacking` `#security` `#railwayapp` `#responsibledisclosure`
