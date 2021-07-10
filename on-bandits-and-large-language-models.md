# On bandits and large language models

Large language models such as GPT-3 or GPT-J require some degree of _prompt programming_. We could consider a set of K different prompts or configs \(such as the temperature\), as the arms of a bandit, and optimize their selection using Thomson sampling. For this, some feedback will need to be provided by the users \(i.e. rank this generation\).

Moreover, we could also have some degree of context:

* User-related features: mostly the IP, so we could learn preferences.
* Prompt-related features.



