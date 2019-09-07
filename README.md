# judge

## configuration

- `provenian-judge-[env]-env`:

```js
{
  dockerImage: string; // docker image name from dockerhub registry
  instanceImageId: string; // instance image (like Amazon Linux 2) id
  submission_table_name: string; // the name of submission DynamoDB
  judge_queue_name: string; // the name of judge queue
  subnetId: string; // vpc subet id
  vpcId: string; // vpc id
  bucket_name: string; // bucket name for storing problems and submissions
}
```
