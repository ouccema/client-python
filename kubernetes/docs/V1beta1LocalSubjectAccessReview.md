# V1beta1LocalSubjectAccessReview

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**metadata** | [**V1ObjectMeta**](V1ObjectMeta.md) |  | [optional] 
**spec** | [**V1beta1SubjectAccessReviewSpec**](V1beta1SubjectAccessReviewSpec.md) | Spec holds information about the request being evaluated.  spec.namespace must be equal to the namespace you made the request against.  If empty, it is defaulted. | 
**status** | [**V1beta1SubjectAccessReviewStatus**](V1beta1SubjectAccessReviewStatus.md) | Status is filled in by the server and indicates whether the request is allowed or not | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


