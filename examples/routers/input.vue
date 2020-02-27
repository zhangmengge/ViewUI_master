<template>
    <!--<div>-->
        <!--<Input v-model="value" placeholder="Enter something..." style="width: 300px"></Input>-->
        <!--<Input v-model="value11">-->
            <!--<span slot="prepend">http://</span>-->
            <!--<span slot="append">.com</span>-->
        <!--</Input>-->
        <!--<br>-->
        <!--<Input v-model="value12">-->
            <!--<Select v-model="select1" slot="prepend" style="width: 80px">-->
                <!--<Option value="http">http://</Option>-->
                <!--<Option value="https">https://</Option>-->
            <!--</Select>-->
            <!--<Select v-model="select2" slot="append" style="width: 70px">-->
                <!--<Option value="com">.com</Option>-->
                <!--<Option value="org">.org</Option>-->
                <!--<Option value="io">.io</Option>-->
            <!--</Select>-->
        <!--</Input>-->
        <!--<br>-->
        <!--<Input v-model="value13">-->
            <!--<Select v-model="select3" slot="prepend" style="width: 80px">-->
                <!--<Option value="day">Day</Option>-->
                <!--<Option value="month">Month</Option>-->
            <!--</Select>-->
            <!--<Button slot="append" icon="ios-search"></Button>-->
        <!--</Input>-->
        <!--<br>-->

        <!--<Input v-model="value11" size="small">-->
        <!--<span slot="prepend">http://</span>-->
        <!--<span slot="append">.com</span>-->
        <!--</Input>-->
        <!--<br>-->
        <!--<Input v-model="value12" size="small">-->
        <!--<Select v-model="select1" slot="prepend" style="width: 80px">-->
            <!--<Option value="http">http://</Option>-->
            <!--<Option value="https">https://</Option>-->
        <!--</Select>-->
        <!--<Select v-model="select2" slot="append" style="width: 70px">-->
            <!--<Option value="com">.com</Option>-->
            <!--<Option value="org">.org</Option>-->
            <!--<Option value="io">.io</Option>-->
        <!--</Select>-->
        <!--</Input>-->
        <!--<br>-->
        <!--<Input v-model="value13" size="small">-->
        <!--<Select v-model="select3" slot="prepend" style="width: 80px">-->
            <!--<Option value="day">Day</Option>-->
            <!--<Option value="month">Month</Option>-->
        <!--</Select>-->
        <!--<Button slot="append" icon="ios-search"></Button>-->
        <!--</Input>-->
        <!--<br>-->

        <!--<Input v-model="value11" size="large">-->
        <!--<span slot="prepend">http://</span>-->
        <!--<span slot="append">.com</span>-->
        <!--</Input>-->
        <!--<br>-->
        <!--<Input v-model="value12" size="large">-->
        <!--<Select v-model="select1" slot="prepend" style="width: 80px">-->
            <!--<Option value="http">http://</Option>-->
            <!--<Option value="https">https://</Option>-->
        <!--</Select>-->
        <!--<Select v-model="select2" slot="append" style="width: 70px">-->
            <!--<Option value="com">.com</Option>-->
            <!--<Option value="org">.org</Option>-->
            <!--<Option value="io">.io</Option>-->
        <!--</Select>-->
        <!--</Input>-->
        <!--<br>-->
        <!--<Input v-model="value13" size="large">-->
        <!--<Select v-model="select3" slot="prepend" style="width: 80px">-->
            <!--<Option value="day">Day</Option>-->
            <!--<Option value="month">Month</Option>-->
        <!--</Select>-->
        <!--<Button slot="append" icon="ios-search"></Button>-->
        <!--</Input>-->
        <!--<br>-->
    <!--</div>-->

    <!--<div>-->
        <!--<Input-->
                <!--v-model="value"-->
                <!--size="small"-->
                <!--prefix="ios-contact"-->
                <!--suffix="ios-search"-->
                <!--placeholder="Enter something..."-->
                <!--style="width: 300px"></Input>-->
        <!--<br>-->
        <!--<Input-->
                <!--v-model="value"-->
                <!--prefix="ios-contact"-->
                <!--suffix="ios-search"-->
                <!--placeholder="Enter something..."-->
                <!--style="width: 300px"></Input>-->
        <!--<br>-->
        <!--<Input-->
                <!--v-model="value"-->
                <!--size="large"-->
                <!--prefix="ios-contact"-->
                <!--suffix="ios-search"-->
                <!--placeholder="Enter something..."-->
                <!--style="width: 300px"></Input>-->
        <!--<br><br>-->
        <!--<Input-->
                <!--v-model="value"-->
                <!--size="small"-->
                <!--icon="ios-search"-->
                <!--placeholder="Enter something..."-->
                <!--style="width: 300px"></Input>-->
        <!--<br>-->
        <!--<Input-->
                <!--v-model="value"-->
                <!--icon="ios-search"-->
                <!--placeholder="Enter something..."-->
                <!--style="width: 300px"></Input>-->
        <!--<br>-->
        <!--<Input-->
                <!--v-model="value"-->
                <!--size="large"-->
                <!--icon="ios-search"-->
                <!--placeholder="Enter something..."-->
                <!--style="width: 300px"></Input>-->
        <!--<br><br><br>-->
        <!--<Input v-model="value" placeholder="Enter something..." style="width: 300px">-->
            <!--<Icon type="ios-alarm-outline" slot="suffix" />-->
            <!--<Icon type="ios-aperture" slot="prefix" />-->
        <!--</Input>-->
        <!--<br><br><br><br>-->
        <!--<Input v-model="value" search enter-button style="width: 300px" @on-search="hs" size="small" />-->
        <!--<br>-->
        <!--<Input v-model="value" search enter-button style="width: 300px" @on-search="hs" />-->
        <!--<br>-->
        <!--<Input v-model="value" search enter-button style="width: 300px" @on-search="hs" size="large" />-->
        <!--<br><br>-->
        <!--<Input v-model="value" search style="width: 300px" @on-search="hs" />-->
        <!--<br><br>-->
        <!--<Input v-model="value" search enter-button="Search" style="width: 300px" @on-search="hs" />-->
    <!--</div>-->
    <div style="width: 200px">
        <Input v-model="value1" type="textarea" :autosize="true" placeholder="Enter something..." @on-enter="changeInput"></Input>
        <Input v-model="value2" type="textarea" :autosize="true" placeholder="Enter something..." @on-enter="changeInput"></Input>
        <Input v-model="value3" type="textarea" :autosize="true" placeholder="Enter something..." @on-enter="changeInput"></Input>
        <Input v-model="value4" type="textarea" :autosize="true" placeholder="Enter something..." @on-enter="changeInput"></Input>
        <Input v-model="value5" type="textarea" :autosize="true" placeholder="Enter something..." @on-enter="changeInput"></Input>
        <input type="button" value="提交" @click="hs"></input>
    </div>
</template>
<script>
    import  axios  from 'axios';
    export default {
        data () {
            return {
                value1: '',
                value2:'',
                value3:'',
                value4:'',
                value5:''
            };
        },
        methods: {
            hs (val) {
                axios.get('http://127.0.0.1:5000/test', {
                    params: {
                        request_header:this.value1,
                        request_method:this.value2,
                        request_url:this.value3,
                        request_params:this.value4,
                        response_code:this.value5,
                    }
                })
                    .then(function (response) {
                        // eslint-disable-next-line no-console
                        console.log(response);
                    })
                    .catch(function (error) {
                        // eslint-disable-next-line no-console
                        console.log(error);
                    });
                // eslint-disable-next-line no-console
                console.log(val);
            },
            changeInput(){
                alert(1111);
            }
        }
    };
</script>
