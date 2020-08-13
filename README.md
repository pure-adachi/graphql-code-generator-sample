# graphql-code-generator-sample

## Quick Start

### Clone

```sh
$ git clone https://github.com/pure-adachi/graphql-code-generator-sample.git
$ cd graphql-code-generator-sample/
$ mkdir -p projects
$ cd projects/
$ git clone https://github.com/pure-adachi/graphql-code-generator-sample-frontend.git
$ git clone https://github.com/pure-adachi/graphql-code-generator-sample-backend.git
```

### Directory Structure

```
graphql-code-generator-sample
└── projects
  ├── graphql-code-generator-sample-backend
  └── graphql-code-generator-sample-frontend
```

### Project Setup

```sh
$ yarn dc-build
$ yarn dc-setup
```

### Database Setup

```sh
$ yarn db-reset
```

#### Project Start

```sh
$ yarn dc-up
```

Please access in [http://localhost:3000](http://localhost:3000)
