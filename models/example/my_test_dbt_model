{{ config(materialized='table') }}

with account_data as (

    select id as id
    from TABLE RAW.SALESFORCE.ACCOUNT

)

select *
from account_data
