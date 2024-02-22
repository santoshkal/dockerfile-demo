## Validating and Generating Dockerfile for AuthorService
```shell
./genval --mode container --reqinput https://raw.githubusercontent.com/santoshkal/dockerfile-demo/main/dockerfile-inputs/author-dockerfile.json \
--output ./dockerfiles/author-Dockerfile \
--inputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/inputfile_policies.rego \
--outputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/dockerfile_policies.rego
```

## Validating and Generating Dockerfile for BookService
```shell
./genval --mode container --reqinput https://raw.githubusercontent.com/santoshkal/dockerfile-demo/main/dockerfile-inputs/booksvc-dockerfile.json \
--output ./dockerfiles/book-Dockerfile \
--inputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/inputfile_policies.rego \
--outputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/dockerfile_policies.rego
```

## Validating and Generating Dockerfile for GenreService
```shell
./genval --mode container --reqinput https://raw.githubusercontent.com/santoshkal/dockerfile-demo/main/dockerfile-inputs/genre-dockerfile.json \
--output ./dockerfiles/genre-Dockerfile \
--inputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/inputfile_policies.rego \
--outputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/dockerfile_policies.rego
```

## Validating and Generating Dockerfile for PublisherService
```shell
./genval --mode container --reqinput https://raw.githubusercontent.com/santoshkal/dockerfile-demo/main/dockerfile-inputs/publisher-dockerfile.json \
--output ./dockerfiles/publisher-Dockerfile \
--inputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/inputfile_policies.rego \
--outputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/dockerfile_policies.rego
```

## Validating and Generating Dockerfile for RatingService
```shell
./genval --mode container --reqinput https://raw.githubusercontent.com/santoshkal/dockerfile-demo/main/dockerfile-inputs/rating-dockerfile.json \
--output ./dockerfiles/rating-Dockerfile \
--inputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/inputfile_policies.rego \
--outputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/dockerfile_policies.rego
```


## Validating and Generating Dockerfile for UserService
```shell
./genval --mode container --reqinput https://raw.githubusercontent.com/santoshkal/dockerfile-demo/main/dockerfile-inputs/user-dockerfile.json \
--output ./dockerfiles/rating-Dockerfile \
--inputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/inputfile_policies.rego \
--outputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/dockerfile_policies.rego
```

# Validating Dockerfiles induvisually
`./genval --mode dockerval --reqinput ./dockerfiles/author-Dockerfile --outputpolicy https://raw.githubusercontent.com/intelops/genval-security-policies/patch-1/default-policies/rego/dockerfile_policies.rego`
