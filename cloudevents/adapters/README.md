# CloudEvents Adapters

<!-- no verify-specs -->

Not all event producers will produce CloudEvents natively. As a result,
some "adapter" might be needed to convert these events into CloudEvents.
This will typically mean extracting metadata from the events to be used as
CloudEvents attributes. In order to promote interoperability across multiple
implementations of these adapters, the following documents show the proposed
algorithms that should be used:

- [AWS S3](./aws-s3.md)
- [AWS SNS](./aws-sns.md)
- [CouchDB](./couchdb.md)
- [GitHub](./github.md)
- [GitLab](./gitlab.md)
