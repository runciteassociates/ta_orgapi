# Total Access Organization API

## Prerequisites

* You should understand what are [WebHooks](https://webhooks.pbworks.com/w/page/13385124/FrontPage) and how to receive/parse them on the back end.
* You should understand [Protocol Buffers](https://developers.google.com/protocol-buffers/docs/proto3) and [gRPC](https://grpc.io/docs/guides/concepts/).
* You should have `protoc` compiler with support for gRPC and your programming language of choice installed. See examples on [gRPC website](https://grpc.io/docs/quickstart/go/).
* Get gRPC server URL from your Total Access contact.

## Contents

* webhooks/biz_operation.json - example of HTTP webhook;
* proto/entities.proto - set of domain entities used within the API;
* proto/google/* - (auxiliary) set of Google protocol buffers used by domain entities;
* proto/access_logs.proto - Access Logs gRPC service definitions;
* proto/biz_operations.proto - Biz Operations gRPC service definitions;
* proto/checkpoints.proto - Checkpoints gRPC service definitions;
* proto/indoor_sessions.proto - Indoor Sessions gRPC service definitions;
* proto/organizations.proto - Organizations gRPC service definitions;
* proto/schedules.proto - Schedules gRPC service definitions;
* proto/security_cameras.proto - Security Cameras gRPC service definitions;
* proto/security_devices.proto - Security Devices gRPC service definitions;
* proto/sessions.proto - Sessions (sign in/out) gRPC service definitions;
* proto/user_groups.proto - User Groups gRPC service definitions;
* proto/user_Group_sets.proto - User Group Sets gRPC service definitions;
* proto/users.proto - Users gRPC service definitions;
