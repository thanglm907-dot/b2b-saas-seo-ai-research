# Kevin Indig — LinkedIn Post #2

**Author:** Kevin Indig  
**Profile:** https://www.linkedin.com/in/kevinindig/  
**Post URL:** https://www.linkedin.com/posts/kevinindig_a-prompt-tracker-that-runs-each-prompt-once-share-7469012961387511808-14kf/  
**Date:** June 2025  
**Topic:** AI prompt tracking methodology, measuring LLM visibility accurately

---

## Post Content

A prompt tracker that runs each prompt once is measuring volatility, not visibility.

I looked at 815,000 prompt-page pairs with AirOps. After the same prompt ran 3x in ChatGPT, only 2.2% of citations remained.

Accuracy improves when you treat each prompt like a sample: run it 3-5 times, report confidence intervals, and keep the raw answers for audit. The goal is to measure variance instead of avoiding it.

Full guide in this week's Growth Memo.

---

## Key Takeaways

- Running a prompt once = measuring **volatility**, not actual visibility
- Data: 815,000 prompt-page pairs analyzed — only **2.2% of citations remained** consistent after running the same prompt 3x in ChatGPT
- LLM answers are highly volatile — single-run tracking is unreliable
- **Correct methodology:**
  - Run each prompt 3-5 times
  - Report confidence intervals (not single results)
  - Keep raw answers for audit trail
- Goal = measure **variance**, not eliminate it
- Implication for B2B SaaS: AI visibility tracking tools that run prompts once are giving false data

