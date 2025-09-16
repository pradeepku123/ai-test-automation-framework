# ai-test-automation-framework
- Ai Framework to test Generative AI

# Project Sector
ai-test-automation-framework/
│── README.md
│── requirements.txt
│── pytest.ini
│
├── config/
│   └── settings.yaml        # model endpoint, API key, configs
│
├── tests/
│   ├── test_regression.py   # regression & similarity tests
│   ├── test_safety.py       # jailbreak, toxicity, PII checks
│   └── test_performance.py  # latency & throughput
│
├── tools/
│   ├── adversarial_generator.py  # adversarial prompt generator
│   ├── safety_utils.py           # PII + toxicity checks
│   └── metrics.py                # semantic similarity utils
│
└── ci/
    └── github-actions.yml   # GitHub Actions workflow
