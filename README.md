# shared-configuration
Shared configuration(e.g. angular, react and other general settings) for docker build.

## Project Structure
```
.
├── gitlab-ci/
│   ├── env/
│   │   ├── beta.yml
│   │   ├── beta2.yml
│   │   ├── prod.yml
│   │   ├── prod2.yml
│   │   ├── release.yml
│   │   ├── test.yml
│   │   └── test2.yml
│   ├── gcr.yml
│   ├── job.yml
│   ├── pipeline-dev.yml
│   ├── pipeline.yml
│   ├── regional-job.yml
│   ├── template.yml
│   └── tests/
│       ├── go.yml
│       └── js.yml
├── nginx/
│   └── spa.conf
├── LICENSE
└── README.md
```
