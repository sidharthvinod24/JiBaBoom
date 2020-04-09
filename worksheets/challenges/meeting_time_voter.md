# Challenges

You are given the set of input and a few queries. Fill in the results based on the input and queries.

# Basic

## Basic Input

| availabilityId | participantId | meetingId  | startTime | endTime |
| -------------- | ------------- | ---------- | --------- | ------- |
| 1000000001     | 1100000001    | 1110000001 | 1000      | 1045    |
| 1000000002     | 1100000001    | 1110000001 | 1030      | 1100    |
| 1000000003     | 1100000002    | 1110000001 | 1030      | 1115    |
| 1000000004     | 1100000002    | 1110000001 | 1100      | 1130    |
| 1000000005     | 1100000001    | 1110000002 | 1000      | 1100    |
| 1000000006     | 1100000002    | 1110000002 | 1100      | 1200    |
| 1000000007     | 1100000003    | 1110000002 | 1200      | 1300    |
| 1000000008     | 1100000004    | 1110000003 | 1000      | 1100    |
| 1000000009     | 1100000005    | 1110000003 | 1045      | 1230    |
| 1000000010     | 1100000006    | 1110000003 | 1030      | 1200    |
| 1000000011     | 1100000007    | 1110000003 | 1100      | 1500    |
| 1000000012     | 1100000008    | 1110000004 | 1000      | 1100    |
| 1000000013     | 1100000009    | 1110000004 | 1045      | 1230    |
| 1000000014     | 1100000010    | 1110000004 | 1030      | 1200    |
| 1000000015     | 1100000011    | 1110000004 | 1100      | 1500    |
| 1000000016     | 1100000012    | 1110000004 | 1600      | 1700    |

## Basic Query 1

| Attribute | Value      |
| --------- | ---------- |
| meetingId | 1110000001 |
| duration  | 30         |

## Basic Result 1

fromTime: 1030
toTime: 1100
participants: ?, ?

## Basic Query 2

| Attribute | Value      |
| --------- | ---------- |
| meetingId | 1110000002 |
| duration  | 60         |

## Basic Result 2

fromTime: ?
toTime: ?
participants: ?

## Basic Query 3

| Attribute | Value      |
| --------- | ---------- |
| meetingId | 1110000003 |
| duration  | 15         |

## Basic Result 3

fromTime: ?
toTime: ?
participants: ?

## Basic Query 4

| Attribute | Value      |
| --------- | ---------- |
| meetingId | 1110000004 |
| duration  | 15         |

## Basic Result 4

fromTime: ?
toTime: ?
participants: ?

## Advance Input

| availabilityId | participantId | meetingId  | startTime | endTime |
| -------------- | ------------- | ---------- | --------- | ------- |
| 1000000001     | 1100000001    | 1110000001 | 1000      | 1045    |
| 1000000002     | 1100000001    | 1110000001 | 1030      | 1100    |
| 1000000003     | 1100000002    | 1110000001 | 1030      | 1115    |
| 1000000004     | 1100000002    | 1110000001 | 1100      | 1130    |
| 1000000005     | 1100000001    | 1110000002 | 1000      | 1100    |
| 1000000006     | 1100000002    | 1110000002 | 1100      | 1200    |
| 1000000007     | 1100000003    | 1110000002 | 1200      | 1300    |
| 1000000008     | 1100000004    | 1110000003 | 1000      | 1100    |
| 1000000009     | 1100000005    | 1110000003 | 1045      | 1230    |
| 1000000010     | 1100000006    | 1110000003 | 1030      | 1200    |
| 1000000011     | 1100000007    | 1110000003 | 1100      | 1500    |
| 1000000012     | 1100000008    | 1110000004 | 1000      | 1100    |
| 1000000013     | 1100000009    | 1110000004 | 1045      | 1230    |
| 1000000014     | 1100000010    | 1110000004 | 1030      | 1200    |
| 1000000015     | 1100000011    | 1110000004 | 1100      | 1500    |
| 1000000016     | 1100000012    | 1110000004 | 1600      | 1700    |

## Advance Query 1

| Attribute | Value      |
| --------- | ---------- |
| meetingId | 1110000001 |
| duration  | 30         |
| fromTime  | 1000       |
| toTime    | 1200       |

## Advance Result 1

fromTime: ?
toTime: ?
participants: ?

## Advance Query 2

| Attribute | Value      |
| --------- | ---------- |
| meetingId | 1110000002 |
| duration  | 60         |
| fromTime  | 1000       |
| toTime    | 1300       |

## Advance Result 2

fromTime: ?
toTime: ?
participants: ?

## Advance Query 3

| Attribute | Value      |
| --------- | ---------- |
| meetingId | 1110000003 |
| duration  | 15         |
| fromTime  | 1000       |
| toTime    | 1200       |

## Advance Result 3

fromTime: ?
toTime: ?
participants: ?

## Advance Query 4

| Attribute | Value      |
| --------- | ---------- |
| meetingId | 1110000004 |
| duration  | 15         |
| fromTime  | 1000       |
| toTime    | 1700       |

## Advance Result 4

fromTime: ?
toTime: ?
participants: ?
