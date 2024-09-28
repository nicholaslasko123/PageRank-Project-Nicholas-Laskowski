# Task 1, part 1:

```bash
$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --verbose
INFO:root:rank=0 pagerank=2.3264e-03 url=www.lawfareblog.com/snowden-revelations
INFO:root:rank=1 pagerank=2.3264e-03 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=2.3264e-03 url=www.lawfareblog.com/topics
INFO:root:rank=3 pagerank=2.3264e-03 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=2.3264e-03 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=2.3264e-03 url=www.lawfareblog.com/masthead
INFO:root:rank=6 pagerank=2.3264e-03 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=7 pagerank=2.3264e-03 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=2.3264e-03 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=2.3264e-03 url=www.lawfareblog.com/documents-related-mueller-investigation
```

# Task 1, part 2:
```bash
$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --search_query='corona'
INFO:root:rank=0 pagerank=6.2949e-05 url=www.lawfareblog.com/lawfare-podcast-united-nations-and-coronavirus-crisis
INFO:root:rank=1 pagerank=6.1454e-05 url=www.lawfareblog.com/house-oversight-committee-holds-day-two-hearing-government-coronavirus-response
INFO:root:rank=2 pagerank=5.9342e-05 url=www.lawfareblog.com/britains-coronavirus-response
INFO:root:rank=3 pagerank=5.9183e-05 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
INFO:root:rank=4 pagerank=5.8976e-05 url=www.lawfareblog.com/israeli-emergency-regulations-location-tracking-coronavirus-carriers
INFO:root:rank=5 pagerank=5.8894e-05 url=www.lawfareblog.com/why-congress-conducting-business-usual-face-coronavirus
INFO:root:rank=6 pagerank=5.8697e-05 url=www.lawfareblog.com/congressional-homeland-security-committees-seek-ways-support-state-federal-responses-coronavirus
INFO:root:rank=7 pagerank=5.8506e-05 url=www.lawfareblog.com/paper-hearing-experts-debate-digital-contact-tracing-and-coronavirus-privacy-concerns
INFO:root:rank=8 pagerank=5.8242e-05 url=www.lawfareblog.com/house-subcommittee-voices-concerns-over-us-management-coronavirus
INFO:root:rank=9 pagerank=5.8176e-05 url=www.lawfareblog.com/lawfare-podcast-bonus-edition-steve-vladeck-emergency-powers-and-coronavirus

$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --search_query='trump'
INFO:root:rank=0 pagerank=1.1426e-04 url=www.lawfareblog.com/document-trump-revokes-obama-executive-order-counterterrorism-strike-casualty-reporting
INFO:root:rank=1 pagerank=1.0906e-04 url=www.lawfareblog.com/trump-administrations-worrying-new-policy-israeli-settlements
INFO:root:rank=2 pagerank=1.0467e-04 url=www.lawfareblog.com/dc-circuit-overrules-district-courts-due-process-ruling-qasim-v-trump
INFO:root:rank=3 pagerank=1.0187e-04 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
INFO:root:rank=4 pagerank=1.0105e-04 url=www.lawfareblog.com/how-trumps-approach-middle-east-ignores-past-future-and-human-condition
INFO:root:rank=5 pagerank=1.0087e-04 url=www.lawfareblog.com/donald-trump-and-politically-weaponized-executive-branch
INFO:root:rank=6 pagerank=1.0010e-04 url=www.lawfareblog.com/why-trump-cant-buy-greenland
INFO:root:rank=7 pagerank=9.6491e-05 url=www.lawfareblog.com/oral-argument-summary-qassim-v-trump
INFO:root:rank=8 pagerank=9.2203e-05 url=www.lawfareblog.com/second-circuit-rules-mazars-must-hand-over-trump-tax-returns-new-york-prosecutors
INFO:root:rank=9 pagerank=9.2137e-05 url=www.lawfareblog.com/dc-circuit-court-denies-trump-rehearing-mazars-case

$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --search_query='iran'
INFO:root:rank=0 pagerank=1.0236e-04 url=www.lawfareblog.com/how-us-iran-tensions-could-disrupt-iraqs-fragile-peace
INFO:root:rank=1 pagerank=1.0063e-04 url=www.lawfareblog.com/praise-presidents-iran-tweets
INFO:root:rank=2 pagerank=8.1918e-05 url=www.lawfareblog.com/cyber-command-operational-update-clarifying-june-2019-iran-operation
INFO:root:rank=3 pagerank=7.0600e-05 url=www.lawfareblog.com/aborted-iran-strike-fine-line-between-necessity-and-revenge
INFO:root:rank=4 pagerank=6.9487e-05 url=www.lawfareblog.com/parsing-state-departments-letter-use-force-against-iran
INFO:root:rank=5 pagerank=6.9262e-05 url=www.lawfareblog.com/announcing-united-states-and-use-force-against-iran-new-lawfare-e-book
INFO:root:rank=6 pagerank=6.9201e-05 url=www.lawfareblog.com/iranian-hostage-crisis-and-its-effect-american-politics
INFO:root:rank=7 pagerank=6.8152e-05 url=www.lawfareblog.com/us-names-iranian-revolutionary-guard-terrorist-organization-and-sanctions-international-criminal
INFO:root:rank=8 pagerank=6.4994e-05 url=www.lawfareblog.com/iran-shoots-down-us-drone-domestic-and-international-legal-implications
INFO:root:rank=9 pagerank=6.4719e-05 url=www.lawfareblog.com/israel-iran-syria-clash-and-law-use-force
```

# Task 1, part 3:
```bash
$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz
INFO:root:rank=0 pagerank=2.3264e-03 url=www.lawfareblog.com/snowden-revelations
INFO:root:rank=1 pagerank=2.3264e-03 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=2.3264e-03 url=www.lawfareblog.com/topics
INFO:root:rank=3 pagerank=2.3264e-03 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=2.3264e-03 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=2.3264e-03 url=www.lawfareblog.com/masthead
INFO:root:rank=6 pagerank=2.3264e-03 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=7 pagerank=2.3264e-03 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=2.3264e-03 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=2.3264e-03 url=www.lawfareblog.com/documents-related-mueller-investigation

$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --filter_ratio=0.2
INFO:root:rank=0 pagerank=6.1839e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1964
INFO:root:rank=1 pagerank=6.1839e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1963
INFO:root:rank=2 pagerank=6.1173e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1962
INFO:root:rank=3 pagerank=4.1380e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1965
INFO:root:rank=4 pagerank=3.6826e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1966
INFO:root:rank=5 pagerank=3.6703e-04 url=www.lawfareblog.com/cyberlaw-podcast-sandworm-and-grus-global-intifada
INFO:root:rank=6 pagerank=3.6694e-04 url=www.lawfareblog.com/cyberlaw-podcast-plumbing-depths-artificial-stupidity
INFO:root:rank=7 pagerank=3.4672e-04 url=www.lawfareblog.com/lawfare-podcast-ben-nimmo-whack-mole-game-disinformation
INFO:root:rank=8 pagerank=3.4672e-04 url=www.lawfareblog.com/lawfare-podcast-week-was-impeachment
INFO:root:rank=9 pagerank=3.2797e-04 url=www.lawfareblog.com/cyberlaw-podcast-mistrusting-google
```

# Task 1, part 4:
```bash
$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --verbose 
INFO:root:rank=0 pagerank=2.3264e-03 url=www.lawfareblog.com/snowden-revelations
INFO:root:rank=1 pagerank=2.3264e-03 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=2.3264e-03 url=www.lawfareblog.com/topics
INFO:root:rank=3 pagerank=2.3264e-03 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=2.3264e-03 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=2.3264e-03 url=www.lawfareblog.com/masthead
INFO:root:rank=6 pagerank=2.3264e-03 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=7 pagerank=2.3264e-03 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=2.3264e-03 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=2.3264e-03 url=www.lawfareblog.com/documents-related-mueller-investigation

$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --verbose --alpha=0.99999
INFO:root:rank=0 pagerank=8.2337e-02 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=1 pagerank=8.2337e-02 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=8.2337e-02 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=3 pagerank=8.2337e-02 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=8.2337e-02 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=8.2337e-02 url=www.lawfareblog.com/masthead
INFO:root:rank=6 pagerank=8.2337e-02 url=www.lawfareblog.com/topics
INFO:root:rank=7 pagerank=8.2337e-02 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=8.2337e-02 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=9 pagerank=8.2337e-02 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site

$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --verbose --filter_ratio=0.2
INFO:root:rank=0 pagerank=6.1839e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1964
INFO:root:rank=1 pagerank=6.1839e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1963
INFO:root:rank=2 pagerank=6.1173e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1962
INFO:root:rank=3 pagerank=4.1380e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1965
INFO:root:rank=4 pagerank=3.6826e-04 url=www.lawfareblog.com/todays-headlines-and-commentary-1966
INFO:root:rank=5 pagerank=3.6703e-04 url=www.lawfareblog.com/cyberlaw-podcast-sandworm-and-grus-global-intifada
INFO:root:rank=6 pagerank=3.6694e-04 url=www.lawfareblog.com/cyberlaw-podcast-plumbing-depths-artificial-stupidity
INFO:root:rank=7 pagerank=3.4672e-04 url=www.lawfareblog.com/lawfare-podcast-ben-nimmo-whack-mole-game-disinformation
INFO:root:rank=8 pagerank=3.4672e-04 url=www.lawfareblog.com/lawfare-podcast-week-was-impeachment
INFO:root:rank=9 pagerank=3.2797e-04 url=www.lawfareblog.com/cyberlaw-podcast-mistrusting-google

$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --filter_ratio=0.2 --alpha=0.99999
INFO:root:rank=0 pagerank=3.2868e-01 url=www.lawfareblog.com/covid-19-speech-and-surveillance-response
INFO:root:rank=1 pagerank=3.2868e-01 url=www.lawfareblog.com/lawfare-live-covid-19-speech-and-surveillance
INFO:root:rank=2 pagerank=4.9087e-02 url=www.lawfareblog.com/cost-using-zero-days
INFO:root:rank=3 pagerank=1.4886e-02 url=www.lawfareblog.com/lawfare-podcast-former-congressman-brian-baird-and-daniel-schuman-how-congress-can-continue-function
INFO:root:rank=4 pagerank=1.0911e-02 url=www.lawfareblog.com/events
INFO:root:rank=5 pagerank=7.5731e-03 url=www.lawfareblog.com/water-wars-increased-us-focus-indo-pacific
INFO:root:rank=6 pagerank=7.5724e-03 url=www.lawfareblog.com/water-wars-drill-maybe-drill
INFO:root:rank=7 pagerank=7.5695e-03 url=www.lawfareblog.com/water-wars-disjointed-operations-south-china-sea
INFO:root:rank=8 pagerank=7.5668e-03 url=www.lawfareblog.com/water-wars-song-oil-and-fire
INFO:root:rank=9 pagerank=7.5668e-03 url=www.lawfareblog.com/water-wars-sinking-feeling-philippine-china-relations
```

# Task 2, part 1:
```bash
$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona'
INFO:root:rank=0 pagerank=2.4042e-02 url=www.lawfareblog.com/britains-coronavirus-response
INFO:root:rank=1 pagerank=2.4042e-02 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
INFO:root:rank=2 pagerank=2.3406e-02 url=www.lawfareblog.com/chinatalk-how-party-takes-its-propaganda-global
INFO:root:rank=3 pagerank=2.2222e-02 url=www.lawfareblog.com/brexit-not-immune-coronavirus
INFO:root:rank=4 pagerank=2.2222e-02 url=www.lawfareblog.com/rational-security-my-corona-edition
INFO:root:rank=5 pagerank=2.1527e-02 url=www.lawfareblog.com/lawfare-podcast-united-nations-and-coronavirus-crisis
INFO:root:rank=6 pagerank=1.9412e-02 url=www.lawfareblog.com/paper-hearing-experts-debate-digital-contact-tracing-and-coronavirus-privacy-concerns
INFO:root:rank=7 pagerank=1.8840e-02 url=www.lawfareblog.com/israeli-emergency-regulations-location-tracking-coronavirus-carriers
INFO:root:rank=8 pagerank=1.8145e-02 url=www.lawfareblog.com/china-responds-coronavirus-iron-grip-information-flow
INFO:root:rank=9 pagerank=1.7149e-02 url=www.lawfareblog.com/house-oversight-committee-holds-day-two-hearing-government-coronavirus-response
```

# Task 2, part 2:
```bash
$ python3 pagerank.py --data=/Users/nicholaslaskowski/Desktop/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona' --search_query='-corona'
INFO:root:rank=0 pagerank=2.3406e-02 url=www.lawfareblog.com/chinatalk-how-party-takes-its-propaganda-global
INFO:root:rank=1 pagerank=1.5916e-02 url=www.lawfareblog.com/covid-19-speech-and-surveillance-response
INFO:root:rank=2 pagerank=1.5915e-02 url=www.lawfareblog.com/lawfare-live-covid-19-speech-and-surveillance
INFO:root:rank=3 pagerank=1.3845e-02 url=www.lawfareblog.com/trump-cant-reopen-country-over-state-objections
INFO:root:rank=4 pagerank=1.1996e-02 url=www.lawfareblog.com/fault-lines-foreign-policy-quarantined
INFO:root:rank=5 pagerank=9.1445e-03 url=www.lawfareblog.com/chinatalk-dispatches-shanghai-beijing-and-hong-kong
INFO:root:rank=6 pagerank=8.6927e-03 url=www.lawfareblog.com/limits-world-health-organization
INFO:root:rank=7 pagerank=7.8378e-03 url=www.lawfareblog.com/fault-lines-combating-extremism-farah-pandith
INFO:root:rank=8 pagerank=7.8378e-03 url=www.lawfareblog.com/twitter-using-health-emergency-settle-political-scores
INFO:root:rank=9 pagerank=7.8378e-03 url=www.lawfareblog.com/lawfare-podcast-stephen-holmes-liberalism-21st-century
```
