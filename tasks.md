# 7/3 task list

- [ ] finish public data cleaning outside the Sedap room
      - My initial idea was to generate only one dataset with four datasets (SISU adoption, AA adoption, program level info and SISU weights) merged . However, we have different unique obs levels, and the merge generated some problems.  Therefore, I decided to create 4 separate files. I saved all them in data/tmp. The code I used to clean these data is 0_clean_public_data_CESUP_AA_SISU. Some issues: there are approximately 400 programs where vacancies through SISU are higher than total vacancies. Also, almost 30% of federal programs did not have a corresponding SISU weight (even if I only use weights in 2016). My idea is to input weights using the most frequency weights for the same program name. 
- [ ] scheduled email to send to Sedap asking to put the following docs in Sedap room 
- [ ] scheduled email to Felipe to get RAIS authorization
